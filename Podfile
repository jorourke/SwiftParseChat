use_frameworks!
platform :ios, '8.0'



target 'SwiftParseChat' do
    pod 'Alamofire'
    pod 'APAddressBook'
    pod 'Bolts'
    pod 'JSQMessagesViewController'
    pod 'JSQSystemSoundPlayer'

    pod 'FBSDKCoreKit'
    pod 'FBSDKLoginKit'
    pod 'FBSDKShareKit'
    pod 'FBAudienceNetwork'

    pod 'Parse'
    pod 'ParseUI'
    pod 'ParseCrashReporting'
    pod 'ParseFacebookUtilsV4'
end

post_install do |installer|
  installer.pods_project.build_configuration_list.build_configurations.each do |configuration|
    configuration.build_settings['CLANG_ALLOW_NON_MODULAR_INCLUDES_IN_FRAMEWORK_MODULES'] = 'YES'

  end
end
