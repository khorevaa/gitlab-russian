Локализация GitLab 8.5.3
---
Путь для замены в Centos 7:

	/opt/gitlab/embedded/service/gitlab-rails/app/

Для обновления Assets:

	chmod -R 1777 /opt/gitlab/embedded/service/gitlab-rails/public/assets`

	gitlab-rake assets:precompile RAILS_ENV=production`
	
	gitlab-ctl restart`
