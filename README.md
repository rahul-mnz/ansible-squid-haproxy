# Ansible Script For Squid and HAProxy Setup

<h1>Steps to Run Squid Automation Script</h1>
<ol>
    <li> Update the list of servers in myhosts file under Squid group.</li>
    <li> Check the ansible.cfg and update the remote_user.</li>
    <li> Uncomment "private_key_file = /path/to/key " under defaults section of ansible.cfg file if required.</li>
    <li> Update variables in squid_vars.yml file as per requirement</li>
    <li> Run - "ansible-playbook squid.yml" to start the script. Add --check in cmd if need to check the output without running. </li>
</ol>