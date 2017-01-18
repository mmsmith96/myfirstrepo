mkdir /tmp/myfirstrepo
cd /tmp/myfirstrepo
echo "This is my first file." > myfile.tx
git init
ls .git # A look at what we've done.
git commit -am 'Initial commit.'
