# encoding: utf-8

desc 'S3デプロイ'
task :deploy do
    sh 'aws s3 sync ./ s3://separatr.com/ --exclude ".git/*" --exclude "Rakefile" --delete --grants read=uri=http://acs.amazonaws.com/groups/global/AllUsers'
end
