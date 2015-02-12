require "bundler/gem_tasks"

desc "Fetch new version from https://github.com/tombatossals/angular-leaflet-directive"
task :fetch do
  source = "https://raw.githubusercontent.com/tombatossals/angular-leaflet-directive/master/dist/angular-leaflet-directive.js"
  target = "vendor/assets/javascripts/angular-leaflet-directive.js"
  sh "curl #{source} > #{target}"
end
