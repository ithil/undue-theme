{exec} = require 'child_process'
puts = (str) -> console.log str

task 'build', "Build project", ->
  exec 'sass --update sass:css', (err, stdout, stderr) ->
    throw err if err
    puts stdout + stderr
