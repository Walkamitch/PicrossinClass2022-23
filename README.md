# dynamicControls (This is Heading 1 - one hashtag)
## Actually this is the start to picross (This is Heading 2 - two hashtags)
### Picross is a fun game (This is Heading 3 - three hashtags)

I really enjoy the game **picross** we created it in *Mr. Klins' epic programming class* - Two asterisks for bold, one asterisk for italic
Here is the order of our approach
1. We played [Picross](http://liouh.com/picross/) online
2. We formulated a loose plan
3. We wrote some together
4. We were tasked with the finishing on our own

Here are a few concepts covered (unordered list):
- Custom classes (for the spaces)
- Inheritance (used by spaces to inherit button proporties)
- Lists (2 dimensional)

Here is some sample code of the starting template for our space class
` Public Class picrossButton
    Inherits Button

    Private _clicked As Boolean = False
    Public Property good As Boolean = False
    Public Property clicked As Boolean
        Get
            Return _clicked
        End Get
        Set(value As Boolean)
            _clicked = value
            If _clicked Then
                Me.Enabled = False
                If good Then
                    Me.BackColor = Color.Green
                Else
                    Me.BackColor = Color.Red
                End If
            Else
                Me.BackColor = Control.DefaultBackColor
            End If
        End Set
    End Property
End Class`

Here is a link to a [markdown cheat sheet:](https://www.markdownguide.org/cheat-sheet/)
 
