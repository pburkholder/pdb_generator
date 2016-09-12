chef generate cookbook -g $HOME/Projects/pburkholder/chef_cookbook_generator ckbk
....
eval $(docker-machine env default)
chef gem install kitchen-dokken
export KITCHEN_LOCAL_YAML=.kitchen.dokken.yml
