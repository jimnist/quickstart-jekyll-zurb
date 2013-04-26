
desc "deploy site to server"
task :deploy do
  system "rsync -avz -e ssh site/. tg-admin:/usr/share/nginx/www"
end