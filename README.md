eSports App
===========

eSports app made with Apache Flex 4.14.1 and Adobe AIR 17.0

How to use:

1. Clone the 'src' folder somewhere in your computer.

2. Create a new Flex Mobile project with the name you desire.

3. Select 'Blank' as application template and click on Finish.

4. Replace the 'src' folder from the new project you just created with the one you downloaded/cloned from this repo.

5. You must provide your own UI icons, all of them should go in the 'assets/icons' folder.

When you try to compile the app for the first time it will throw several errors, all of them are from missing assets.

To bypass these you can modify the MXML like this:

source="@Embed('assets/icons/someicon.png')" to source="assets/icons/someicon.png"


Notes:

You need a Youtube V3 Data APiKEY. You can generate a free one from your Google Developers Console.
This project can teach you how to use SQLite, HTTPServices, JSON parsing, Lazy Loading and some performance optimizations.
