example_project_path = 'Examples/GMObjCDemo'
test_project_path = 'Tests/GMObjCTests'
workspace 'GMObjC.xcworkspace'

use_frameworks!

# Example Project
target 'GMObjC iOS Demo' do
  project example_project_path
  platform :ios, '9.0'
  pod 'GMObjC', :path => './'
end

# Test Project
target 'Tests Host' do
  project test_project_path
  platform :ios, '9.0'
  pod 'GMObjC', :path => './'
end

target 'Tests iOS' do
  project test_project_path
  platform :ios, '9.0'
  pod 'GMObjC', :path => './'
end
