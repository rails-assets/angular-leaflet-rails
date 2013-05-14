require "bundler/gem_tasks"

desc "Fetch new version from https://github.com/tombatossals/angular-leaflet-directive"
task :fetch do
  source = "https://raw.github.com/tombatossals/angular-leaflet-directive/master/src/angular-leaflet-directive.js"
  target = "vendor/assets/javascripts/angular-leaflet-directive.js"
  sh "curl #{source} > #{target}"
end
