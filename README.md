# Ionic 5 Star Rating

This library was forked from https://github.com/JeongJun-Lee/ionic5-star-rating/ for a simple modification.

## Install

Run `npm install --save https://github.com/arthurcipolari/ionic5-star-rating/tarball/master`

## How to use

Basically, same as https://github.com/melwinVincent/ionic4-star-rating/blob/master/README.md

But, there are three changes. 

First, Use this selector `ionic5-star-rating` in HTML template.

Second, the event of ionic4-star-rating was removed because the Events was deprecated in Ionic 5. So you can't subscribe it anymore.

Third, removed half star for rating, now even if using half star for better visuals when you click it rates with integers only.
