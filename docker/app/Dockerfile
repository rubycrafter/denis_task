FROM rails

WORKDIR /app

EXPOSE 3000
CMD sleep 5 && bundle install --path /gems && rake db:migrate && rails s -b 0.0.0.0
