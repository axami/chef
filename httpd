package "httpd" do
  action :install
end

file "/var/www/html/index.html"
  content "Yet another new CM"
  action :create
end

service "httpd" do
  action :start
end
