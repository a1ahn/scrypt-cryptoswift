def import_pods
  pod 'CryptoSwift', '~> 0.10'
end

target 'scrypt' do
  platform :osx, '10.11'
#  use_frameworks!
  use_modular_headers!
  import_pods

  target 'scryptTests' do
    inherit! :search_paths
    # Pods for testing
  end

end
