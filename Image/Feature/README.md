# VLAN vs IPv4
* Mỗi tầng có 1 vlan. 
* Phòng server, phòng giám sát, thiết bị Cam có 1 vlan riêng (Vlan Admin).  
* Vlan10: 192.168.10.0/24  
* Vlan20: 192.168.20.0/24  
* Vlan30: 192.168.30.0/24  
* Vlan40: 192.168.40.0/24  
* Vlan50: 192.168.10.0/24  
* Vlan60: 192.168.20.0/24  
* Vlan70: 192.168.30.0/24  
* Admin: 192.168.2.0/24
* Core Switch GigabitEthernet0/1: 172.16.1.2/24
* Local on Firewall: 172.16.1.1/24
* Inside on Firewall: 172.17.1.1/24
* Outside on Firewall: 10.10.10.1/24 (Quên đây là Private IP đáng lẽ nên config khác)
# Inter-vlan
* On core switch.
# Network Access Control List
* On core switch.
* Các thiết bị thường không được phép truy cập vào Vlan Admin.
# IOT system
* IOT server ở tầng 1 phòng server.  
* Tất cả các thiết bị IOT đều kết nối với IOT server.  
* Các cảm biến dùng giao thức mqtt để quản lý.
* Phần mềm quản lý được viết bằng python (Packet router hỗ trợ).
* Máy lạnh cũng được kết nối với IOT server.  
* Các thiết bị IOT được thiết kế để cứ mỗi 2 phút sẽ gửi đến IOT server thông tin hiện tại.  
# Camera system
* CAM server ở tầng 1 phòng server.  
* Tất cả thiết bị camera đều kết nối với CAM server.  
# PAT 
* Pat on firewall
