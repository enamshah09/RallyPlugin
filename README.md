# Rally Plugin

This Plugin will install Rally and run the Live Migration Plugin. 

## **Steps**

Assuming you have [multi-node devstack install](https://docs.openstack.org/devstack/latest/guides/multinode-lab.html).

After you clone remember to change the IP of the controller in credentials.json

1. `git clone https://github.com/enamshah09/RallyPlugin.git /opt/ownPlugin`
2. cd /opt/ownPlugin
3. `mv setupLvmEnv.sh /opt`
4. `mv vars.rc /opt`
5. cd /opt
6. `./setupLvmEnv.sh`

