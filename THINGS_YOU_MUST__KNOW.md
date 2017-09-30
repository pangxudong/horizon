some tips you have to know:
===========================

1. If you want to deploy and debug this project, first you should run command:`git checkout -b stable/kilo origin/stable/kilo` to checkout the kilo branch.

2. then, run `./run_tests.sh` to set up the environment, you may meet up with a few dependency bugs, fix it these by yourself.ignore the warnings while run tests.

3. next, you should download a project: 'https://github.com/pangxudong/django_openstack_auth.git', and replace `.venv/local/lib/python2.7/site_packages/openstack_auth` with its openstack_auth directory.

4. finally, change the password 'secret' in `openstack_dashboard/local/local_settings.py` and '.venv/local/lib/python2.7/site_packages/openstack_auth/account.py' with the real ones.

5. the 'up.sh' can start the django web server for debugging nirc-horizon
