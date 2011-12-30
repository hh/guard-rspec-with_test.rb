guard 'rspec',
  :spec_paths => ['test/unit'],
  :cli =>  '--pattern "test/unit/*_test.rb" --pattern "test/unit/**/*_test.rb"' do
  watch(%r{^test/unit/.+_test\.rb$})
end
# guard 'rspec', :cli => '--pattern "spec/**/*_test.rb" --pattern "test/unit/**/*_test.rb"' do
#   watch(%r{^spec/.+_test\.rb$})
#   watch(%r{^test/unit/.+_test\.rb$})
# end
