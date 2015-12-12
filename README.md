# chai-mocha-basics
A Basic Project With Chai Mocha Testing


1.Create a new repository in GIThub

2.Do Clone Using The Below Command

	$git clone <git SSH>

3.Create Directory "chai-mocha-basics"

	$cd chai-mocha-basics

4.View List Of Files In The Directory

	$ls -la

5.Open Sublime Editor

	$subl.

6.Use The Below Command To Create "package.json" File

	$npm init

7.View List Of Files In The Directory

	$ls -la

8.View Created "package.json" file

	$cat package.json

9.Install Mocha Chai Through NPM

	$npm install mocha chai --save


10.Create a new folder "test" and create "test.js"

  Sample Code
  
  	var expect = require('chai').expect;
  	describe('A basic test', function(){
  		it('should pass when everything is okay', function(){
  			expect(true).to.be.true;
  		});
  	});

11.Use Below Commands To Run Test

	$mocha
	$npm test

12.Use Below Commands To Push Code To The Repository

	$git status
	$git add --all
	$git commit -a -m "Commit Description"
	$git push

