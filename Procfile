web: erb conf/nginx.conf.erb > conf/nginx.conf && touch logs/access.log logs/error.log && (tail -f -n 0 logs/*.log &) && objs/nginx -p .
