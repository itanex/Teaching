# Filtering ENHANCED! + Authentication

* Take the ng-lesson-04 repository and correct the data file so that it contains valid serializable dates
   * Dates labeled in the data as unreleased should be null values
   * Dates with some content should be established with Month Day and Year. Javascript may asked for a Time just set it to * midnight.
* Update games.model.ts so that the releasedate fields are Date types instead of Strings
* Update the table to filter the display of these dates so that they display as the following:
   * MONTH YEAR -> in the case there is a date
   * Unreleased -> in the case there is NO date
* Make the Game Module protect by authentication