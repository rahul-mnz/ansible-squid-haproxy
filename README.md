# Ansible Script For Squid and HAProxy Setup

<h1>Steps to Run Squid Automation Script</h1>
<ol>
    <li>1. Update the list of servers in myhosts file under Squid group.</li>
    <li>2. Check the ansible.cfg and update the remote_user.</li>
    <li>3. Uncomment "private_key_file = /path/to/key " under defaults section of ansible.cfg file if required.</li>
    <li>4. Update variables in squid_vars.yml file as per requirement</li>
    <li>5. Run - "ansible-playbook squid.yml" to start the script. Add --check in cmd if need to check the output without running. </li>
</ol>