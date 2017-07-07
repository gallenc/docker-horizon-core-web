 see https://docs.opennms.org/opennms/releases/20.0.0/guide-install/guide-install.html#gi-install-minion-configure
 
 because the minion is ephemeral it needs to be given credentials at  start up. Unfortunately restarting the minion will remove the credentials. Hence we give generic credentials minion minion to get things going