build:
	cd ../cookbooks/my_wrapper && berks vendor ../../packer/vendor
	packer build rails-demo.json | tee packer-output.log
