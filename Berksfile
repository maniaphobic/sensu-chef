source 'https://supermarket.chef.io'
metadata

cookbook 'chef-vault', path: "#{Dir.getwd}/test/cookbooks/chef-vault"
cookbook 'ms_dotnet', path: "#{Dir.getwd}/test/cookbooks/ms_dotnet"
cookbook 'redisio', path: "#{Dir.getwd}/test/cookbooks/redisio"

group :integration do
  cookbook "sensu-test", path: "test/cookbooks/sensu-test"
end
