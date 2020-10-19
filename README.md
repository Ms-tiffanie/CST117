# CST117

<Global.Microsoft.VisualBasic.CompilerServices.DesignerGenerated()> _
Partial Class Form1
    Inherits System.Windows.Forms.Form

    'Form overrides dispose to clean up the component list.
    <System.Diagnostics.DebuggerNonUserCode()> _
    Protected Overrides Sub Dispose(ByVal disposing As Boolean)
        Try
            If disposing AndAlso components IsNot Nothing Then
                components.Dispose()
            End If
        Finally
            MyBase.Dispose(disposing)
        End Try
    End Sub

    'Required by the Windows Form Designer
    Private components As System.ComponentModel.IContainer

    'NOTE: The following procedure is required by the Windows Form Designer
    'It can be modified using the Windows Form Designer.  
    'Do not modify it using the code editor.
    <System.Diagnostics.DebuggerStepThrough()> _
    Private Sub InitializeComponent()
        Me.lblHeader = New System.Windows.Forms.Label()
        Me.txtFahrenheit = New System.Windows.Forms.TextBox()
        Me.txtCelsius = New System.Windows.Forms.TextBox()
        Me.lblFahrenheit = New System.Windows.Forms.Label()
        Me.Label1 = New System.Windows.Forms.Label()
        Me.hsbScroller = New System.Windows.Forms.HScrollBar()
        Me.btnExit = New System.Windows.Forms.Button()
        Me.SuspendLayout()
        '
        'lblHeader
        '
        Me.lblHeader.AutoSize = True
        Me.lblHeader.Font = New System.Drawing.Font("Times New Roman", 15.75!, System.Drawing.FontStyle.Bold, System.Drawing.GraphicsUnit.Point, CType(0, Byte))
        Me.lblHeader.Location = New System.Drawing.Point(311, 33)
        Me.lblHeader.Name = "lblHeader"
        Me.lblHeader.Size = New System.Drawing.Size(155, 24)
        Me.lblHeader.TabIndex = 0
        Me.lblHeader.Text = "Temp Converter"
        '
        'txtFahrenheit
        '
        Me.txtFahrenheit.BackColor = System.Drawing.SystemColors.ButtonHighlight
        Me.txtFahrenheit.Font = New System.Drawing.Font("Microsoft Sans Serif", 9.75!, System.Drawing.FontStyle.Bold, System.Drawing.GraphicsUnit.Point, CType(0, Byte))
        Me.txtFahrenheit.Location = New System.Drawing.Point(220, 158)
        Me.txtFahrenheit.Name = "txtFahrenheit"
        Me.txtFahrenheit.ReadOnly = True
        Me.txtFahrenheit.Size = New System.Drawing.Size(77, 22)
        Me.txtFahrenheit.TabIndex = 1
        Me.txtFahrenheit.Text = "32.0"
        '
        'txtCelsius
        '
        Me.txtCelsius.BackColor = System.Drawing.SystemColors.ButtonHighlight
        Me.txtCelsius.Font = New System.Drawing.Font("Microsoft Sans Serif", 9.75!, System.Drawing.FontStyle.Bold, System.Drawing.GraphicsUnit.Point, CType(0, Byte))
        Me.txtCelsius.Location = New System.Drawing.Point(489, 158)
        Me.txtCelsius.Name = "txtCelsius"
        Me.txtCelsius.ReadOnly = True
        Me.txtCelsius.Size = New System.Drawing.Size(77, 22)
        Me.txtCelsius.TabIndex = 2
        Me.txtCelsius.Text = "0"
        Me.txtCelsius.TextAlign = System.Windows.Forms.HorizontalAlignment.Center
        '
        'lblFahrenheit
        '
        Me.lblFahrenheit.AutoSize = True
        Me.lblFahrenheit.BackColor = System.Drawing.SystemColors.ButtonHighlight
        Me.lblFahrenheit.Font = New System.Drawing.Font("Times New Roman", 14.25!, System.Drawing.FontStyle.Bold, System.Drawing.GraphicsUnit.Point, CType(0, Byte))
        Me.lblFahrenheit.Location = New System.Drawing.Point(207, 249)
        Me.lblFahrenheit.Name = "lblFahrenheit"
        Me.lblFahrenheit.Size = New System.Drawing.Size(99, 22)
        Me.lblFahrenheit.TabIndex = 3
        Me.lblFahrenheit.Text = "Fahrenheit"
        '
        'Label1
        '
        Me.Label1.AutoSize = True
        Me.Label1.BackColor = System.Drawing.SystemColors.ButtonHighlight
        Me.Label1.Font = New System.Drawing.Font("Times New Roman", 15.75!, System.Drawing.FontStyle.Bold, System.Drawing.GraphicsUnit.Point, CType(0, Byte))
        Me.Label1.Location = New System.Drawing.Point(554, 236)
        Me.Label1.Name = "Label1"
        Me.Label1.Size = New System.Drawing.Size(67, 24)
        Me.Label1.TabIndex = 4
        Me.Label1.Text = "celsius"
        '
        'hsbScroller
        '
        Me.hsbScroller.Location = New System.Drawing.Point(200, 309)
        Me.hsbScroller.Maximum = 300
        Me.hsbScroller.Minimum = -100
        Me.hsbScroller.Name = "hsbScroller"
        Me.hsbScroller.Size = New System.Drawing.Size(434, 49)
        Me.hsbScroller.TabIndex = 5
        '
        'btnExit
        '
        Me.btnExit.Font = New System.Drawing.Font("Times New Roman", 12.0!, System.Drawing.FontStyle.Bold, System.Drawing.GraphicsUnit.Point, CType(0, Byte))
        Me.btnExit.Location = New System.Drawing.Point(678, 395)
        Me.btnExit.Name = "btnExit"
        Me.btnExit.Size = New System.Drawing.Size(75, 23)
        Me.btnExit.TabIndex = 6
        Me.btnExit.Text = "Exit"
        Me.btnExit.UseVisualStyleBackColor = True
        '
        'frmTempConverter
        '
        Me.AutoScaleDimensions = New System.Drawing.SizeF(6.0!, 13.0!)
        Me.AutoScaleMode = System.Windows.Forms.AutoScaleMode.Font
        Me.BackColor = System.Drawing.SystemColors.ActiveCaption
        Me.ClientSize = New System.Drawing.Size(800, 450)
        Me.Controls.Add(Me.btnExit)
        Me.Controls.Add(Me.hsbScroller)
        Me.Controls.Add(Me.Label1)
        Me.Controls.Add(Me.lblFahrenheit)
        Me.Controls.Add(Me.txtCelsius)
        Me.Controls.Add(Me.txtFahrenheit)
        Me.Controls.Add(Me.lblHeader)
        Me.Name = "frmTempConverter"
        Me.Text = "Temperature Converter"
        Me.ResumeLayout(False)
        Me.PerformLayout()

    End Sub

    Friend WithEvents lblHeader As Label
    Friend WithEvents txtFahrenheit As TextBox
    Friend WithEvents txtCelsius As TextBox
    Friend WithEvents lblFahrenheit As Label
    Friend WithEvents Label1 As Label
    Friend WithEvents hsbScroller As HScrollBar
    Friend WithEvents btnExit As Button
End Class
