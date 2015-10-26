# YoloWebDev HW3: README
Team Members: Gil Olaes, Jason Tan, Max Takano, Alexie Sousa, Sam Marks

This README describes the use of YoloWebDev's HW3 website.

## Access

The pages in question can be accessed by the following methods:

1. Through the zip file sent to the professor and TA's
2. By visiting the project's github page (https://github.com/violetgil/CSE134B_HW3)
3. By visiting the hosted version of the project (http://cse134b-hw3.co.nf/landing.html)

# The Project

## General Design

While looking through the wireframes, we realized that we would need to add a lot more color in order to make the project more visually appealing.  To that end we redesigned the logo around the concept of good (virtues) versus evil (vices), linking them to a blue and red design scheme.  Most of the rest of the website has also been designed with this in mind.

We've also slightly changed the layout of the site to make it more universally responsive to desktops and tablets, as well as mobile devices.  For example, we've added a header and footer to every page in order to make a more tablet and desktop friendly design and then designed them to scale well into a mobile view.  Also, the logo located in the header can also be clicked to navigate the user back to the landing page as a sort of home button to help navigation.  Other than that, we've outlined some page specific changes below.

## The Web Pages

The project consists of 3 pages, outlined below:

### Landing Page (landing.html)

The landing page includes the redesigned logo, as well as buttons that help the user navigate to both the habit creation and habit viewing pages.  The layout is largely unchanged from the wireframe except for slight spacing changes on the horizontal rules in the middle of the screen.  It's also important to note that the horizontal rule, as well as the buttons, will scale by screen size so that the text and buttons are always readable and on single lines.

Included in the code of the page, but not implemented or shown, is a set of login inputs that are contained in the header that would allow a user to sign into the application.  While the code exists to place them onto the page, problems with responsivity keep us from adding it into this release.

### Habit Creation Page (addhabit.html)

The habit creation page is structurally very similar to the wireframe, with all of the logos and buttons for each section lined up on one row, overflowing to the right for users to be able to swipe through as necessary.  One minor change that we made was for every row of buttons (including the frequency and weekly rows) to scroll across the screen in order to keep those rows consistent with the icon row.  Finally, we've added more frequency buttons in order to accomodate activities that should happen more than 3 times a day and then added basic validation to all the inputs so that a user cannot accidentally add an activity before they have finished filling in all the information for it.  Once a user submits a valid set of inputs, this mock-up takes them straight to the habit viewing page.

Note that, since we haven't created a back-end for the application yet, none of the user input is stored, saved, or used inside any of the other pages in the application.

### Habit Viewing Page (habit.html)

The habit viewing page is also very similar to the wireframe.  Clicking on either the thumbs up and thumbs down will cause both buttons to disappear and be replaced by a percentage and meter showing the ratio between thumbs up presses and thumbs down presses.  Pressing the meter will cause it to disappear and revert to showing the thumbs up and thumbs down buttons.  The edit and delete buttons, which are always visible in the desktop and tablet versions but require a swipe to view in the mobile version, perform approximately the functions they are supposed to.  The edit button will take the user to the habit creation page (although the lack of a back-end prevents us from pre-populating the page with information), and the delete button will remove the row from the page.

In terms of changes, we've centered the name of each habit and its frequency in order to make it more visible and pronounced and made it so that you can reset the thumbs up and thumbs down buttons by pressing on the meter.

For right now, the page has been pre-populated with dummy rows in order to get a feel for what the page will look like on completion.
