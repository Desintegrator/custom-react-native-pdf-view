# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'RNPDFView' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for RNPDFView
  pod 'React', :path => '../node_modules/react-native', :subspecs => [
    'Core',
    'CxxBridge', # Include this for RN >= 0.47
    'DevSupport', # Include this to enable In-App Devmenu if RN >= 0.43
    'RCTText',
    'RCTNetwork',
    'RCTWebSocket', # needed for debugging
    # Add any other subspecs you want to use in your project
  ]
  # Explicitly include Yoga if you are using RN >= 0.42.0
  pod "yoga", :path => "../node_modules/react-native/ReactCommon/yoga"


end
