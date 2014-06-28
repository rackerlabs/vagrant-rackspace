versions = {
  '1.6'    => 'v1.6.3',
  '1.5'    => 'v1.5.3',
  '1.4'    => 'v1.4.3',
  '1.3'    => 'v1.3.5',
  '1.2'    => 'v1.2.7',
  'master' => 'master'
}

versions.each do |version_alias, vagrant_tag|
  appraise "vagrant_#{version_alias}" do
    gem 'vagrant', :git => 'git://github.com/mitchellh/vagrant.git', :branch => vagrant_tag
  end
end
