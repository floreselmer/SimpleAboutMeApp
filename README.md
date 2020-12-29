# Simple app that displays my name and changes coloring in the background

Create the AboutMe app.
1)Added TextView to the layout to display your name.
The LinearLayout has the required attributes layout_height, layout_width, and orientation, which is vertical by default. 3. Switch to the Design tab to open the Layout Editor.
In the Resources dialog, select Add new resource > New string Value.
In the New String Value Resource dialog, set the Resource name field to name. Set the Resource value field to your own name. Click OK. Notice that the warning is gone.
<string name="name">Elmer Flores</string>

Added an ImageView.
Display the layout file In the Design tab, then drag an ImageView from the Palette pane to below name_text in the Component Tree. The Resources dialog opens.
Select Drawable if it's not already selected.
Expand android, scroll, and select btn_star_big_on. It's the yellow star 

Added a ScrollView to display scrollable text.
Open the activity_main.xml file in the Design tab.
Drag a scroll view into the layout by dragging it into the design editor, or into the Component Tree. Put the scroll view below the star image.
<ScrollView
   android:layout_width="match_parent"
   android:layout_height="match_parent">

   <LinearLayout
       android:layout_width="match_parent"
       android:layout_height="wrap_content"
       android:orientation="vertical" />
</ScrollView>
