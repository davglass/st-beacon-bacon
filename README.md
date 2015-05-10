Beacon Bacon
------------

A little POC SmartApp that uses [Beecon+](http://www.beaconsandwich.com/beecon+.html) to ping SmartThings
via iBeacons and turn on light switches. It was just a POC to show that we could actually do this.

Install
=======

   * Create the SmartApp from the code
   * Install the `Beecon+` iOS app

Install the SmartApp
====================

   * Install the SmartApp
   * Select the switch to turn on
   * Grab the oAuth URL, needed for `Beecon+`

Beecon+ Setup
=============

   * Setup the Region, no notifications
   * On the Beacon screen, select your beacon
   * Give it a name
   * And Color
   * When In Range
      * Minimum Distance, I chose `Near`
      * Do: Select Call URL
      * Paste in the oAuth URL from the SmartApp
    * When Out Of Range
      * Do: Select Call URL
      * Paste in the oAuth URL from the SmartApp
    * Save Everything
    * Open The Preferences
       * More Options
       * Select "URL actions POST vars"
       * Save
    * Give it a shot
