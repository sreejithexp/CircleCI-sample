# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'CircleCI-Sample' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

    pod 'Alamofire', '~> 4.7'
  # Pods for CircleCI-Sample

end
post_install do |installer| installer.pods_project.build_configurations.each do |config| config.build_settings['PROVISIONING_PROFILE_SPECIFIER'] = '' end end


