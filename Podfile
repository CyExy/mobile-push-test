# Uncomment this line to define a global platform for your project
platform :ios, '8.3'
# Uncomment this line if you're using Swift
use_frameworks!

target 'push' do
    pod 'Google/CloudMessaging'
    pod 'React', :path => './ReactComponents/node_modules/react-native', :subspecs => [
        'Core',
        'RCTImage',
        'RCTNetwork',
        'RCTText',
        'RCTWebSocket'
    ], :tag => '0.23.1'
end

target 'pushTests' do

end

target 'pushUITests' do

end
