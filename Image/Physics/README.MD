# H6
* Được thiết kế gồm các thiết bị: access point, switch layer 2, switch layer 3 (thay cho router), tường lửa, máy lạnh, camera giám sát, cảm biến nhiệt độ, cảm biến ánh sáng.  
* Có 7 tầng trong đó có 3 tầng đặc biệt tầng 1, tầng 6, tầng 7.
* Trong các tầng có 5 loại phòng: phòng nhỏ, phòng lớn, phòng thực hành, phòng giám sát, phòng server.  
* Các switch tầng sẽ nối với 1 switch layer 3 tổng, switch layer 3 sẽ kết nối với tường lửa rồi đi ra ngoài.

# Phòng nhỏ
* Gồm 1 access point, 1 cảm biến ánh sáng, 1 cảm biến nhiệt độ.
# Phòng Lớn
* Gồm 1 access point, 2 cảm biến ánh sáng, 2 cảm biến nhiệt độ.
# Phòng thực hành
* Gồm 1 access point, máy lạnh, 2 cảm biến ánh sáng, 2 cảm biến nhiệt độ.
# Phòng server
* Gồm 1 switch kết nối các server.
# Phòng giám sát
* Gồm 1 switch kết nối với các thiết bị giám sát.

# Tầng 1 
* Có phòng nhỏ, phòng lớn và phòng server.  
* Có 1 switch layer 2 tổng cho 1 tầng.  
* Có camera và 1 switch cho camera nối với trực tiếp switch tầng.  
* Các thiết bị nối kết mạng không dây wifi đến access point. Các access point sẽ nối với switch tầng.  
* Switch phòng server cũng nối trực tiếp đến switch tầng.  
# Các tầng từ tầng 2-5
* Các Phòng nhỏ và phóng lớn (demo chỉ 1 phòng lớn 1 phòng nhỏ).
* Có 1 switch layer 2 tổng cho 1 tầng.  
* Có camera và 1 switch cho camera hành lang nối với trực tiếp switch tổng.
* Các thiết bị nối kết mạng không dây wifi đến access point. Các access point sẽ nối với switch tổng.
# Tầng 6
* Có phòng nhỏ, phòng lớn và phòng thực hành (demo chỉ 1 phòng lớn, 1 phòng nhỏ, 1 phòng TH).
* Tương tự cách nối dây các tầng dưới.
# Tầng 7
* Có phòng nhỏ, phòng lớn, phòng thực hành và phòng giám sát.
* Tương tự cách nối dây các tầng dưới.


