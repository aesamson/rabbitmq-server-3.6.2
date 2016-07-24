# rabbitmq-server-3.6.2

To install rabbitmq-server-3.6.2 on gentoo arm architecture please follow steps listed below:<br>
<ol>
<li><b>Create directory</b> <code>mkdir -p /usr/local/portage/net-misc/rabbitmq-server</code></li>
<li><b>Download patch</b> <code>wget https://github.com/aesamson/rabbitmq-server-3.6.2/archive/master.zip</code></li>
<li><b>Unzip archive</b> <code>unzip master.zip</code></li>
<li><b>Copy all content</b> <code>cp -r rabbitmq-server-3.6.2-master/* /usr/local/portage/net-misc/rabbitmq-server</code></li>
<li><b>Move to</b> <code>cd /usr/local/portage/net-misc/rabbitmq-server</code></li>
<li><b>Download sources</b> <code>wget http://www.rabbitmq.com/releases/rabbitmq-server/v3.6.2/rabbitmq-server-3.6.2.tar.xz</code></li>
<li><strike><b>Create Manifest file</b> <code>ebuild /usr/local/portage/net-misc/rabbitmq-server-3.6.2.ebuild digest</code></strike></li>
<li><b>Emerge rabbitmq-server</b> <code>emerge rabbitmq-server</code></li>
</ol>
