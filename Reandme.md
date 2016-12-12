##########################################################################################################                                                                             #                                                                                                        #
#                                                                                                        #
#                                  Common User                                                           #
#                                                                                                        #
#                                                                                                        #
##########################################################################################################

##################### About Playbook #########################
This Playbook will create a user based on the tags for example environment_prod or environment_dev or environment_tst
####################Changes that need to take care whike running #################
Since username is not updating dynamically we have to hard code the username in YML file for now.
We have to place the instance keypairs in keypair folder and public key file in roles/common_user/file folder.
##########################command to run this playbook###############
ansible-playbook -i /home/sivasankar/ansible-Commonuser/ec2.py /home/sivasankar/ansible-Commonuser/commonuser.yml *****
