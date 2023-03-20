# Continuous Assessment 1

Student Name: Bruno Almeida
Student ID: 24845
Course: Science in Computing

## Requirement Checklist

- [x ] Home page
    - [ x] Show profile photo: With atleast 5dp separation from the layout
    - [x ] Your Details: horizontally centered in layout
        - [ x] Name
        - [x ] Course
        - [ 1/2] Github Icon (SVG Vector) and username
    - [x ] Four buttons — Education, Skills, Achievements and Exit
        - [ x] vertically stacked
        - [ x] same size
        - [ x] separated vertically by atleast 5dp
        - [ x] Education, Skills, Achievements take to new page
        - [ x] Exit should close the app
    - [x ] Copyright text at bottom:
        - [ x] Text: (c) 2023 Your name. All rights reserved.
        - [ x] has a small font size
        - [ x] has dark gray color
        - [ x] has a top padding 10dp with a top gray border of 1dp (to separate it out from the main content)
- [ x] Education, Skills, and Achievement pages contain:
    - [ 1/2] title row: not scrollable, dark bg, light icon and text, horizontally centered
    - [ ] content: scrollable
        - [ ] Feel free to add your own content
        - [ ] Skills page should have Android Studio with icon
    - [ x] button row: not scrollable, 3 buttons — Previous, Home, Next
        - [x ] Prev button hidden on the first page
        - [ x] Next button hidden on the last page
        - [ x] Home button goes back to home (without creating new page)
- [ ] Bonus
    - [ ] Use at least one FrameLayout as a separator e.g. to separate two LinearLayouts or TextViews (Hint: Set height 1dp with a light gray background)
    - [ ] Show both icon and text in buttons

- I added an android extension to help me with my codding this one id 'kotlin-android-extensions'
- and to work i has to implement this on my build.grade app file 
- android {
  buildFeatures {
  viewBinding true
  }
  }


