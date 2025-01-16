# Gilded Rose Refactoring Kata

Welcome to the Gilded Rose Kata! This is an inventory management system that manages several different kinds of items. Different kinds of items have different rules governing how their quality changes over time. Some of the items depreciate in quality over time, and some of them appreciate, but no one knows which is which anymore. Any original requirements documents are long gone, as are the developers who wrote the original code.

A new requirement came in recently to add support for a new kind of item called `Conjured Mana Cake`. A "conjured" item degrades twice as quickly as normal items. Your task is to implement this requirement.

Kent Beck says to "make the change easy, then make the easy change." Start by refactoring the existing code to make it easy to understand the current items and to add a new kind of item. Then, make the easy change by adding the new "conjured" item type.

## To run

Clone this repo, then `cd` into the `php` directory and run `docker compose up`. Then, as you change PHP files, you'll see output in your terminal window indicating whether the tests are passing. Try to make changes that are as small and atomic as possible while keeping the tests passing. The most important goal of this exercise is to evolve this code using _small, incremental_ steps rather than large rewrites. (One example of a small step to get you started: try extracting the body of the `foreach` loop into a separate method.)
