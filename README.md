# test
test 
```mermaid
usecaseDiagram
  actor Owner as O
  actor Staff as S
  actor Tenant as T

  O --> (Quan ly phong)
  O --> (Quan ly khach thue)
  O --> (Quan ly hop dong)
  O --> (Quan ly hoa don)
  O --> (Gui thong bao)
  O --> (Xem thong ke)
  O --> (Dang tin quang ba)
  O --> (Dang nhap/Dang xuat)

  S --> (Quan ly phong)
  S --> (Quan ly khach thue)
  S --> (Quan ly hop dong)
  S --> (Quan ly hoa don)
  S --> (Gui thong bao)
  S --> (Dang nhap/Dang xuat)

  T --> (Nhan thong bao)
  T --> (Gui phan anh)
  T --> (Dang nhap/Dang xuat)
