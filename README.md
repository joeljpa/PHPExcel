# What's here

I simply could could not migrate to PhpSpreadsheet due to my workplace setting.

My workplace's legacy project used PHPExcel a lot and eventually I ended up modifying its core code to change some styling and color schemes which the original version didn't have.

That's what's here. Branch 1.8 is the fork and 1.8.1j is original version code (1.8->1.8.1 if I'm not mistaken) changes along with my changes.

Full credit goes this question at stackoverflow [PHPExcel graph design (border, graph color, graph inner position)](https://stackoverflow.com/q/18612897/8958173). I used [IIIOXIII's answer](https://stackoverflow.com/a/19396447/8958173) and applied [Waqleh's answer](https://stackoverflow.com/a/39392781/8958173) to make my own custom class with those said changes, thus keeping the original writer Excel2007 untouched.

*Ending and resuming original readme.*

# PHPExcel - DEAD

PHPExcel last version, 1.8.1, was released in 2015. The project was officially deprecated in 2017 and permanently archived in 2019.

The project has not be maintained for years and must not be used anymore. **All users must migrate** to its direct successor [PhpSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet), or another alternative.

## License

PHPExcel is licensed under [LGPL (GNU LESSER GENERAL PUBLIC LICENSE)](https://github.com/PHPOffice/PHPExcel/blob/master/license.md)
