# bootstrap-grid-100cols-with-xl-and-xxl

A CSS file that contains the <a href='https://v4-alpha.getbootstrap.com/layout/grid/'>bootstrap grid</a> with xlg ( > 1550px width ) and xxlg ( > 2000 px width) classes. The grid is split into columns with 1/100 width of the parent div.

# What is this?

A bootstrap grid where the width of the screen is broken into 100 pieces e.g

`col-xs-70`

will create a div with width 70% of it's parent div.

The grid breakpoints are:

  - xs: less than 768px
  - sm: 768px to 991px,
  - md: 992px to 1199px,
  - lg: 1200px to 1500px,
  - xlg: 1500px to 2000px,
  - xxlg: bigger than 2000px

# Why did you do this?

- I got sick of needing a column with half way between two class widths on the standard 1/12 column width system and then having to hack a custom class for one specific use case so this grid is split into 1/100's.

- I didn't like how lg was the biggest size meaning that everything from a laptop to a large desktop screen was given the same classes.
