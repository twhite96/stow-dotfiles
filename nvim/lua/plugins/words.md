wget https://cdn.gyptazy.com/files/os/debian/proxlb/proxlb_1.0.4_amd64.deb
dpkg -i proxlb_1.0.4_amd64.deb
# Adjust your config
vi /etc/proxlb/proxlb.conf
systemctl restart proxlb
systemctl status proxlb