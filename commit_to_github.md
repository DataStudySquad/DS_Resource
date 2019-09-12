### How to git clone/commit/push to github 

```bash
# clone the repo
cd ~ && git clone https://github.com/DataStudySquad/DS_Resource.git
cd ~ && cd DS_Resource
# create local branch 
git checkout -b my_dev_branch
# do some changes
echo 'this is my test file' >> mytestfile.md
# commit the changes 
git commit -m  'add new test file'
# push to github branch  
git push origin my_dev_branch

```