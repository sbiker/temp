MANUAL INSTALLATION 
------------------------------------------------------------------------------------------
* Install the required dependencies by using the 'bundle' command as follows:

    (ruby -S) bundle install (--path=vendor/bundle --binstubs)


* If you don't have 'bundler' already you might need to install it as follows:
	
    (ruby -S) gem install bundler   (or 'gem install bundler')    


* Once that's done you can run the tests from inside the folder that contains the 'Rakefile' as explained below.
	
	
RUNNING TESTS MANUALLY, example:
------------------------------------------------------------------------------------------
ruby bin/cucumber browser=firefox PROXY=on TARGET_ENV=test --tags @specific_tag --format html > output.html

 with mandatory fields:
    * localte=en/gd/cy
    * TARGET_ENV=int/test/stage/live


