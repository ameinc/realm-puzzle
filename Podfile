# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'RealmPuzzle' do
  use_frameworks!

  pod 'Realm'
  pod 'RealmLoginKit'

end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
  end