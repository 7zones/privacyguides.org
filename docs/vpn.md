---
meta_title: "Đề xuất và so sánh dịch vụ VPN riêng tư, Không tài trợ hay quảng cáo - Privacy Guides"
title: "Dịch vụ VPN"
icon: material/vpn
description: Đây là những dịch vụ VPN tốt nhất để bảo vệ quyền riêng tư và bảo mật trực tuyến của bạn. Find a provider here that isn’t out to spy on you.
cover: vpn.webp
---

Nếu bạn đang tìm kiếm **sự riêng tư** bổ sung từ ISP, trên mạng Wi-Fi công cộng, hoặc trong khi tải tệp torrent, VPN có thể là giải pháp cho bạn miễn là bạn hiểu được những rủi ro liên quan. Chúng tôi nghĩ rằng những nhà cung cấp này vượt trội hơn những nhà cung cấp còn lại:

<div class="grid cards" markdown>

- ![Proton VPN logo](assets/img/vpn/protonvpn.svg){ .twemoji } [Proton VPN](#proton-vpn)
- ![IVPN logo](assets/img/vpn/mini/ivpn.svg){ .twemoji } [IVPN](#ivpn)
- ![Mullvad logo](assets/img/vpn/mullvad.svg){ .twemoji } [Mullvad](#mullvad)

</div>

!!! danger "VPN không cung cấp tính năng ẩn danh"

    Sử dụng VPN sẽ **không** giúp trình duyệt web của bạn duy trì ở chế độ ẩn danh, cũng như không tăng thêm tính bảo mật cho lưu lượng truy cập không bảo mật (HTTP).

    Nếu bạn đang muốn **ẩn danh**, bạn nên sử dụng Tor Browser **thay vì** VPN.

    Nếu bạn muốn tăng cường tính **bảo mật**, bạn phải luôn đảm bảo rằng mình đang kết nối với các trang web sử dụng HTTPS. VPN không phải sự thay thế cho các biện pháp bảo mật.

    [Download Tor](https://www.torproject.org/){ .md-button .md-button--primary } [Câu hỏi về Tor](advanced/tor-overview.md){ .md-button }

[Tổng quan chi tiết về VPN :material-arrow-right-drop-circle:](basics/vpn-overview.md){ .md-button }

## Nhà cung cấp được đề xuất

Những nhà cung cấp mà chúng tôi đề xuất đều sử dụng mã hóa, chấp nhận Monero, hỗ trợ WireGuard & OpenVPN, và không có chính sách ghi nhật ký (log). Đọc [danh sách tiêu chí đầy đủ](#criteria) của chúng tôi để biết thêm thông tin.

### Proton VPN

!!! recommendation annotate

    ![Proton VPN logo](assets/img/vpn/protonvpn.svg){ align=right }

    **Proton VPN** là một đơn vị cạnh tranh mạnh trong lĩnh vực VPN đã đi vào hoạt động từ năm 2016. Proton AG có trụ sở tại Thụy Sĩ và cung cấp những dịch vụ miễn phí có giới hạn cũng như tùy chọn cao cấp nhiều tính năng hơn.

    [:octicons-home-16: Trang chủ](https://protonvpn.com/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://protonvpn.com/privacy-policy){ .card-link title="Chính sách bảo mật" }
    [:octicons-info-16:](https://protonvpn.com/support/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/ProtonVPN){ .card-link title="Mã nguồn" }

    ??? downloads

        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=ch.protonvpn.android)
        - [:simple-appstore: App Store](https://apps.apple.com/app/apple-store/id1437005085)
        - [:simple-github: GitHub](https://github.com/ProtonVPN/android-app/releases)
        - [:simple-windows11: Windows](https://protonvpn.com/download-windows)
        - [:simple-linux: Linux](https://protonvpn.com/support/linux-vpn-setup/)

#### :material-check:{ .pg-green } 71 Quốc gia

Proton VPN có [máy chủ ở 71 quốc gia](https://protonvpn.com/vpn-servers) [hoặc 3 nếu bạn sử dụng gói miễn phí](https://protonvpn.com/free-vpn).(1) Chọn nhà cung cấp VPN có máy chủ gần bạn nhất để giảm độ trễ của lưu lượng truy cập mạng của bạn. Nguyên nhân của điều này là do tuyến đường đến đích ngắn hơn (ít bước nhảy hơn).
{ .annotate }

1. Last checked: 2023-12-21

Chúng tôi cho rằng sẽ tốt hơn cho việc bảo mật khóa cá nhân (private key) của nhà cung cấp VPN nếu họ sử dụng [máy chủ chuyên dụng](https://en.wikipedia.org/wiki/Dedicated_hosting_service), thay vì các giải pháp rẻ hơn như [máy chủ ảo](https://vi.wikipedia.org/wiki/Máy_chủ_ảo).

#### :material-check:{ .pg-green } Kiểm tra độc lập

Kể từ tháng 1 năm 2020, Proton VPN đã trải qua cuộc kiểm tra độc lập được thực hiện bởi SEC Consult. SEC Consult đã tìm thấy một số lỗ hổng có mức rủi ro trung bình và thấp trong các ứng dụng Windows, Android, và iOS, tất cả đều được Proton VPN "sửa đúng cách" trước khi báo cáo được công bố. Không phát hiện được bất kỳ lỗ hổng nào cho phép kẻ tấn công có quyền truy cập vào thiết bị hoặc lưu lượng truy cập của bạn từ xa. Bạn có thể xem các báo cáo riêng lẻ cho từng nền tảng tại [protonvpn.com](https://protonvpn.com/blog/open-source/). Vào tháng 4 năm 2022, Proton VPN đã trải qua [một đợt kiểm tra khác](https://protonvpn.com/blog/no-logs-audit/) và báo cáo được [thực hiện bởi Securitum](https://protonvpn.com/blog/wp-content/uploads/2022/04/securitum-protonvpn-nologs-20220330.pdf). [Securitum](https://research.securitum.com) đã cấp cho ứng dụng của Proton VPN một [thư chứng thực](https://proton.me/blog/security-audit-all-proton-apps) vào ngày 9 tháng 11 năm 2021.

#### :material-check:{ .pg-green } Mã nguồn mở cho máy khách

Proton VPN cung cấp mã nguồn cho máy khách (bao gồm máy để bàn và di động) tại [GitHub](https://github.com/ProtonVPN) của họ.

#### :material-check:{ .pg-green } Chấp nhận tiền mặt

Ngoài việc chấp nhận thanh toán bằng thẻ tín dụng/thẻ ghi nợ, PayPal, và [Bitcoin](advanced/payments.md#other-coins-bitcoin-ethereum-etc), Proton VPN còn chấp nhận **tiền mặt/nội tệ** dưới hình thức thanh toán ẩn danh.

#### :material-check:{ .pg-green } Hỗ trợ WireGuard

Proton VPN chủ yếu hỗ trợ giao thức WireGuard®. [WireGuard](https://www.wireguard.com) là một giao thức mới sử dụng [mật mã học](https://www.wireguard.com/protocol/) tiên tiến nhất. Ngoài ra, WireGuard hướng tới mục tiêu đơn giản hơn và hiệu quả hơn.

Proton VPN [khuyến nghị](https://protonvpn.com/blog/wireguard/) sử dụng WireGuard cùng với dịch vụ của họ. Trên các ứng dụng Windows, macOS, iOS, Android, ChromeOS, và Android TV của Proton VPN, WireGuard là giao thức mặc định; tuy nhiên, ứng dụng Linux của họ không [hỗ trợ](https://protonvpn.com/support/how-to-change-vpn-protocols/) giao thức này.

#### :material-alert-outline:{ .pg-orange } Chuyển tiếp cổng từ xa

Proton VPN hiện chỉ hỗ trợ [chuyển tiếp cổng](https://protonvpn.com/support/port-forwarding/) từ xa tạm thời qua NAT-PMP, với thời gian thuê chỉ 60 giây. Ứng dụng Windows có sẵn tùy chọn giúp bạn dễ dàng thực hiện được điều này, tuy nhiên với các hệ điều hành khác, bạn sẽ cần chạy [NAT-PMP client](https://protonvpn.com/support/port-forwarding-manual-setup/) của riêng mình. Các ứng dụng torrent thường hỗ trợ NAT-PMP nguyên bản.

#### :material-check:{ .pg-green } Lẩn tránh kiểm duyệt

Proton VPN có giao thức [Stealth](https://protonvpn.com/blog/stealth-vpn-protocol/) giúp ích cho các trường hợp mà giao thức VPN như OpenVPN hoặc Wireguard bị chặn. Tính năng stealth (tàng hình) hoạt động bằng cách sử dụng TLS tunnel over TCP khiến nó khó bị chặn hơn ngay cả khi phân tích sâu các gói (DPI).

#### :material-check:{ .pg-green } Ứng dụng di động

Ngoài việc cung cấp các tệp cấu hình OpenVPN tiêu chuẩn, Proton VPN còn có ứng dụng di động cho [App Store](https://apps.apple.com/us/app/protonvpn-fast-secure-vpn/id1437005085), [Google Play](https://play.google.com/store/apps/details?id=ch.protonvpn.android&hl=en_US), và [GitHub](https://github.com/ProtonVPN/android-app/releases) cho phép dễ dàng kết nối với máy chủ của họ.

#### :material-information-outline:{ .pg-blue } Tính năng bổ sung

Ứng dụng máy khách của Proton VPN hiện hỗ trợ xác thực 2 yếu tố trên tất cả các nền tảng ngoại trừ Linux. Proton VPN có máy chủ và trung tâm dữ liệu riêng ở Thụy Sĩ, Iceland và Thụy Điển. Họ cung cấp dịch vụ DNS có tính năng chặn những nội dung và phần mềm độc hại đã biết. Ngoài ra, Proton VPN cũng cung cấp máy chủ "Tor" cho phép bạn dễ dàng kết nối với các trang web [onion](https://vi.wikipedia.org/wiki/.onion), những chúng tôi vẫn thực sự khuyên bạn nên sử dụng [trình duyệt Tor chính thức](https://www.torproject.org/) cho mục đích này.

#### :material-alert-outline:{ .pg-orange } Tính năng Killswitch feature bị hỏng trên máy Mac chạy Intel.

Sự cố hệ thống [có thể xảy ra](https://protonvpn.com/support/macos-t2-chip-kill-switch/) trên các máy Mac chạy Intel khi sử dụng VPN killswitch. Nếu bạn muốn sử dụng tính năng này và bạn đang sử dụng máy Mac có chipset Intel, bạn nên cân nhắc sử dụng dịch vụ VPN khác.

### IVPN

!!! recommendation

    ![IVPN logo](assets/img/vpn/ivpn.svg){ align=right }

    **IVPN** là một nhà cung cấp VPN cao cấp khác, và họ đã hoạt động từ năm 2009. IVPN có trụ sở tại Gibraltar.

    [:octicons-home-16: Trang chủ](https://www.ivpn.net/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://www.ivpn.net/privacy/){ .card-link title="Chính sách bảo mật" }
    [:octicons-info-16:](https://www.ivpn.net/knowledgebase/general/){ .card-link title="Tài liệu"}
    [:octicons-code-16:](https://github.com/ivpn){ .card-link title="Mã nguồn" }

    ??? downloads

        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=net.ivpn.client)
        - [:octicons-moon-16: Accrescent](https://accrescent.app/app/net.ivpn.client)
        - [:simple-appstore: App Store](https://apps.apple.com/app/ivpn-serious-privacy-protection/id1193122683)
        - [:simple-windows11: Windows](https://www.ivpn.net/apps-windows/)
        - [:simple-apple: macOS](https://www.ivpn.net/apps-macos/)
        - [:simple-linux: Linux](https://www.ivpn.net/apps-linux/)

#### :material-check:{ .pg-green } 37 Quốc gia

IVPN có [máy chủ ở 37 quốc gia](https://www.ivpn.net/server-locations).(1) Chọn nhà cung cấp VPN có máy chủ gần bạn nhất để giảm độ trễ của lưu lượng truy cập mạng của bạn. Nguyên nhân của điều này là do tuyến đường đến đích ngắn hơn (ít bước nhảy hơn).
{ .annotate }

1. Last checked: 2023-12-21

Chúng tôi cho rằng sẽ tốt hơn cho việc bảo mật khóa cá nhân (private key) của nhà cung cấp VPN nếu họ sử dụng [máy chủ chuyên dụng](https://en.wikipedia.org/wiki/Dedicated_hosting_service), thay vì các giải pháp rẻ hơn như [máy chủ ảo](https://vi.wikipedia.org/wiki/Máy_chủ_ảo).

#### :material-check:{ .pg-green } Kiểm tra độc lập

IVPN đã trải qua cuộc [kiểm tra không ghi log từ Cure53](https://cure53.de/audit-report_ivpn.pdf) với kết luận được đưa ra là đồng ý với tuyên bố không ghi log của IVPN. IVPN cũng đã hoàn thành [báo cáo kiểm tra toàn diện Cure53](https://cure53.de/summary-report_ivpn_2019.pdf) vào tháng 1 năm 2020. IVPN cũng cho biết họ dự định có [báo cáo thường niên](https://www.ivpn.net/blog/independent-security-audit-concluded) trong tương lai. Một đánh giá sâu hơn đã được tiến hành [vào tháng 4 năm 2022](https://www.ivpn.net/blog/ivpn-apps-security-audit-2022-concluded/) và được tiến hành bởi Cure53 [trên trang web của họ](https://cure53.de/pentest-report_IVPN_2022.pdf).

#### :material-check:{ .pg-green } Mã nguồn mở cho client

Kể từ tháng 2 năm 2020, [tất cả các ứng dụng của IVPN đều là mã nguồn mở](https://www.ivpn.net/blog/ivpn-applications-are-now-open-source). Bạn có thể lấy mã nguồn từ [GitHub](https://github.com/ivpn) của họ.

#### :material-check:{ .pg-green } Chấp nhận tiền mặt và Monero

Ngoài việc chấp nhận thẻ tín dụng/thẻ ghi nợ và PayPal, IVPN còn chấp nhận Bitcoin, **Monero** và **tiền mặt/nội tệ** (với gói năm) dưới dạng hình thức thanh toán ẩn danh.

#### :material-check:{ .pg-green } Hỗ trợ WireGuard

IVPN hỗ trợ giao thức WireGuard®. [WireGuard](https://www.wireguard.com) [WireGuard](https://www.wireguard.com) là một giao thức mới sử dụng [mật mã học](https://www.wireguard.com/protocol/) tiên tiến nhất. Ngoài ra, WireGuard hướng tới mục tiêu đơn giản hơn và hiệu quả hơn.

IVPN [khuyến nghị](https://www.ivpn.net/wireguard/) sử dụng WireGuard với dịch vụ của họ, và do đó giao thức này là mặc định trên tất cả các ứng dụng của IVPN. cũng cung cấp trình tạo cấu hình WireGuard để sử dụng với [ứng dụng](https://www.wireguard.com/install/) WireGuard chính thức.

#### :material-alert-outline:{ .pg-orange } Chuyển tiếp cổng từ xa

IVPN trước đây từng hỗ trợ chuyển tiếp cổng từ xa, nhưng đã loại bỏ tùy chọn này vào [tháng 6 năm 2023](https://www.ivpn.net/blog/gradual-removal-of-port-forwarding). Việc thiếu tính năng này có thể tác động tiêu cực đến một số ứng dụng nhất định, đặc biệt là các ứng dụng ngang hàng như torrent client.

#### :material-check:{ .pg-green } Lẩn tránh kiểm duyệt

IVPN has obfuscation modes using the [v2ray](https://www.v2ray.com/en/index.html) project which helps in situations where VPN protocols like OpenVPN or Wireguard are blocked. Currently this feature is only available on Desktop and [iOS](https://www.ivpn.net/knowledgebase/ios/v2ray/). It has two modes where it can use [VMess](https://guide.v2fly.org/en_US/basics/vmess.html) over QUIC or TCP connections. QUIC là giao thức hiện đại có khả năng kiểm soát tắc nghẽn tốt hơn và do đó có thể nhanh hơn với độ trễ giảm. Chế độ TCP làm cho dữ liệu của bạn xuất hiện dưới dạng lưu lượng HTTP thông thường.

#### :material-check:{ .pg-green } Ứng dụng di động

Ngoài việc cung cấp các tệp cấu hình OpenVPN tiêu chuẩn, IVPN còn có ứng dụng di động cho [App Store](https://apps.apple.com/us/app/ivpn-serious-privacy-protection/id1193122683), [Google Play](https://play.google.com/store/apps/details?id=net.ivpn.client), và [GitHub](https://github.com/ivpn/android-app/releases) cho phép dễ dàng kết nối đến máy chủ của họ.

#### :material-information-outline:{ .pg-blue } Tính năng bổ sung

Ứng dụng của IVPN hỗ trợ xác thực 2 yếu tố (Mullvad thì không). IVPN cũng cung cấp chức năng "[AntiTracker](https://www.ivpn.net/antitracker)", có khả năng chặn các mạng quảng cáo và trình theo dõi từ cấp độ mạng.

### Mullvad

!!! recommendation

    ![Mullvad logo](assets/img/vpn/mullvad.svg){ align=right }

    **Mullvad** là một VPN nhanh và rẻ tiền, tập trung chủ yếu vào tính minh bạch và bảo mật đã đi vào hoạt động từ năm **2009**. Mullvad có trụ sở tại Thụy Điển và không có bản dùng thử miễn phí.

    [:octicons-home-16: Trang chủ](https://mullvad.net){ .md-button .md-button--primary }
    [:simple-torbrowser:](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion){ .card-link title="Onion Service" }
    [:octicons-eye-16:](https://mullvad.net/en/help/privacy-policy/){ .card-link title="Chính sách bảo mật" }
    [:octicons-info-16:](https://mullvad.net/en/help/){ .card-link title="Tài liệu"}
    [:octicons-code-16:](https://github.com/mullvad){ .card-link title="Mã nguồn" }

    ??? downloads

        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=net.mullvad.mullvadvpn)
        - [:simple-appstore: App Store](https://apps.apple.com/app/mullvad-vpn/id1488466513)
        - [:simple-github: GitHub](https://github.com/mullvad/mullvadvpn-app/releases)
        - [:simple-windows11: Windows](https://mullvad.net/en/download/windows/)
        - [:simple-apple: macOS](https://mullvad.net/en/download/macos/)
        - [:simple-linux: Linux](https://mullvad.net/en/download/linux/)

#### :material-check:{ .pg-green } 40 Quốc gia

Mullvad có [máy chủ ở 40 quốc gia](https://mullvad.net/servers/).(1) Chọn nhà cung cấp VPN có máy chủ gần bạn nhất để giảm độ trễ của lưu lượng truy cập mạng của bạn. Nguyên nhân của điều này là do tuyến đường đến đích ngắn hơn (ít bước nhảy hơn).
{ .annotate }

1. Last checked: 2023-12-21

Chúng tôi cho rằng sẽ tốt hơn cho việc bảo mật khóa cá nhân (private key) của nhà cung cấp VPN nếu họ sử dụng [máy chủ chuyên dụng](https://en.wikipedia.org/wiki/Dedicated_hosting_service), thay vì các giải pháp rẻ hơn như [máy chủ ảo](https://vi.wikipedia.org/wiki/Máy_chủ_ảo).

#### :material-check:{ .pg-green } Kiểm tra độc lập

Ứng dụng máy khách VPN của Mullvad đã được Cure53 và Assured AB kiểm tra trong một báo cáo pentest [được công bố tại cure53.de](https://cure53.de/pentest-report_mullvad_v2.pdf). Các nhà nghiên cứu bảo mật đã kết luận:

> Cure53 và Assured AB hài lòng với kết quả kiểm tra và phần mềm để lại ấn tượng tích cực tổng thể. Với những nỗ lực bảo mật từ đội ngũ cốt lõi của Mullvad VPN, những nhà thử nghiệm không còn nghi ngờ gì về việc dự án đang đi đúng hướng từ quan điểm bảo mật.

Vào năm 2020, một cuộc kiểm tra thứ hai [đã diễn ra](https://mullvad.net/blog/2020/6/25/results-available-audit-mullvad-app/) và [báo cáo kiểm tra cuối cùng](https://cure53.de/pentest-report_mullvad_2020_v2.pdf) đã được cung cấp trên trang web của Cure53:

> The results of this May-June 2020 project targeting the Mullvad complex are quite positive. [...] Hệ sinh thái ứng dụng tổng thể được Mullvad sử dụng để lại ấn tượng rõ ràng và có cấu trúc. Cấu trúc tổng thể của ứng dụng giúp bạn dễ dàng tung ra các bản vá và bản sửa lỗi một cách có cấu trúc. Hơn bất cứ điều gì, những gì được Cure53 phát hiện cho thấy tầm quan trọng của việc liên tục kiểm tra và đánh giá lại các vectơ rò rỉ hiện tại để luôn đảm bảo quyền riêng tư của người dùng cuối. Như đã nói, Mullvad đã làm rất tốt việc bảo vệ người dùng cuối khỏi các rò rỉ PII thông thường và các rủi ro liên quan đến quyền riêng tư.

Vào năm 2021, một đợt kiểm tra cơ sở hạ tầng [đã diễn ra](https://mullvad.net/en/blog/2021/1/20/no-pii-or-privacy-leaks-found-cure53s-infrastructure-audit/) và [báo cáo kiểm tra cuối cùng](https://cure53.de/pentest-report_mullvad_2021_v1.pdf) được cung cấp trên trang web của Cure53. Một báo cáo khác đã được công bố [vào tháng 6 năm 2022](https://mullvad.net/en/blog/2022/6/22/vpn-server-audit-found-no-information-leakage-or-logging-of-customer-data/) và có trên [trang web của Assured](https://www.assured.se/publications/Assured_Mullvad_relay_server_audit_report_2022.pdf).

#### :material-check:{ .pg-green } Mã nguồn mở cho client

Mullvad cung cấp mã nguồn cho máy khách (bao gồm máy để bàn và di động) tại [GitHub](https://github.com/mullvad/mullvadvpn-app) của họ.

#### :material-check:{ .pg-green } Chấp nhận tiền mặt và Monero

Ngoài việc chấp nhận thẻ tín dụng/thẻ ghi nợ và PayPal, Mullvad còn chấp nhận Bitcoin, Bitcoin tiền mặt, **Monero** và **tiền mặt/nội tệ** dưới dạng hình thức thanh toán ẩn danh. They also accept Swish and bank wire transfers.

#### :material-check:{ .pg-green } Hỗ trợ WireGuard

Mullvad hỗ trợ giao thức WireGuard®. [WireGuard](https://www.wireguard.com) [WireGuard](https://www.wireguard.com) là một giao thức mới sử dụng [mật mã học](https://www.wireguard.com/protocol/) tiên tiến nhất. Ngoài ra, WireGuard hướng tới mục tiêu đơn giản hơn và hiệu quả hơn.

Mullvad [khuyến nghị](https://mullvad.net/en/help/why-wireguard/) sử dụng WireGuard với dịch vụ của họ. Đây là giao thức mặc định hoặc duy nhất trên các ứng dụng Android, iOS, macOS và Linux của Mullvad, nhưng trên Windows thì bạn phải [bật thủ công](https://mullvad.net/en/help/how-turn-wireguard-mullvad-app/) WireGuard. Mullvad cũng cung cấp trình tạo cấu hình WireGuard để sử dụng với [ứng dụng](https://www.wireguard.com/install/) WireGuard chính thức.

#### :material-check:{ .pg-green } Hỗ trợ IPv6

Mullvad cho phép bạn [truy cập các dịch vụ lưu trữ trên IPv6](https://mullvad.net/en/blog/2014/9/15/ipv6-support/), trái ngược với các nhà cung cấp khác chặn kết nối IPv6.

#### :material-alert-outline:{ .pg-orange } Chuyển tiếp cổng từ xa

Mullvad trước đây từng hỗ trợ chuyển tiếp cổng từ xa, nhưng đã loại bỏ tùy chọn này vào [tháng năm năm 2023](https://mullvad.net/en/blog/2023/5/29/removing-the-support-for-forwarded-ports/). Việc thiếu tính năng này có thể tác động tiêu cực đến một số ứng dụng nhất định, đặc biệt là các ứng dụng ngang hàng như torrent client.

#### :material-check:{ .pg-green } Lẩn tránh kiểm duyệt

Mullvad has obfuscation an mode using [Shadowsocks with v2ray](https://mullvad.net/en/help/shadowsocks-with-v2ray) which may be useful in situations where VPN protocols like OpenVPN or Wireguard are blocked.

#### :material-check:{ .pg-green } Ứng dụng di động

Mullvad công bố ứng dụng cho [App Store](https://apps.apple.com/app/mullvad-vpn/id1488466513) và [Google Play](https://play.google.com/store/apps/details?id=net.mullvad.mullvadvpn), cả hai đều hỗ trợ giao diện dễ sử dụng thay vì yêu cầu bạn định cấu hình kết nối WireGuard theo cách thủ công. Ứng dụng khách Android cũng có sẵn trên [GitHub](https://github.com/mullvad/mullvadvpn-app/releases).

#### :material-information-outline:{ .pg-blue } Tính năng bổ sung

Mullvad rất minh bạch về việc họ [sở hữu hoặc thuê](https://mullvad.net/en/servers/) các nút nào. Họ sử dụng [ShadowSocks](https://shadowsocks.org/) trong cấu hình ShadowSocks + OpenVPN, giúp họ tăng khả năng chống lại tường lửa sử dụng [phân tích sâu các gói](https://en.wikipedia.org/wiki/Deep_packet_inspection) đang cố gắng chặn VPN. Chẳng hạn như, [Trung Quốc đã phải sử dụng một phương pháp khác để chặn máy chủ ShadowSocks](https://github.com/net4people/bbs/issues/22). Bạn cũng có thể truy cập trang web của Mullvad qua Tor tại 
 [o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion).

## Tiêu chí

!!! danger

    Điều quan trọng cần lưu ý là việc sử dụng nhà cung cấp VPN sẽ không khiến bạn ẩn danh nhưng nó sẽ mang lại cho bạn sự riêng tư tốt hơn trong một số trường hợp nhất định. VPN không phải là công cụ cho các hoạt động bất hợp pháp. Đừng ỷ vào chính sách "không ghi nhật ký" (no log).

**Xin lưu ý rằng chúng tôi không liên kết với bất kỳ nhà cung cấp nào mà chúng tôi đề xuất. Điều này cho phép chúng tôi đưa ra các đề xuất hoàn toàn khách quan.** Ngoài các [tiêu chí tiêu chuẩn](about/criteria.md), chúng tôi đã phát triển một bộ yêu cầu rõ ràng đối với bất kỳ nhà cung cấp VPN nào muốn được đề xuất, bao gồm mã hóa mạnh, kiểm tra bảo mật độc lập, công nghệ hiện đại,v.v... Chúng tôi khuyên bạn nên tự làm quen với danh sách này trước khi chọn nhà cung cấp VPN và tiến hành nghiên cứu của riêng mình để đảm bảo nhà cung cấp VPN bạn chọn đáng tin cậy nhất có thể.

### Công nghệ

Chúng tôi yêu cầu tất cả các nhà cung cấp VPN được đề xuất của chúng tôi cung cấp các tệp cấu hình OpenVPN để sử dụng trong mọi máy khách. **Nếu** VPN cung cấp ứng dụng khách tùy chỉnh của riêng họ, chúng tôi yêu cầu killswitch để chặn rò rỉ dữ liệu mạng khi bị ngắt kết nối.

**Điều kiện tối thiểu:**

- Hỗ trợ các giao thức mạnh như WireGuard & OpenVPN.
- Killswitch được tích hợp sẵn cho ứng dụng khách.
- Hỗ trợ đa chặng. Đa chặng rất quan trọng để giữ dữ liệu ở chế độ riêng tư trong trường hợp có một nút bị xâm phạm.
- Nếu máy khách VPN được cung cấp thì chúng phải là [mã nguồn mở](https://vi.wikipedia.org/wiki/Nguồn_mở), giống như phần mềm VPN mà họ thường tích hợp sẵn trong đó. Chúng tôi tin rằng tính khả dụng của [mã nguồn](https://vi.wikipedia.org/wiki/Mã_nguồn) mang lại sự minh bạch cao hơn về những gì thiết bị của bạn thực sự đang làm.

**Trường hợp tốt nhất:**

- Hỗ trợ WireGuard và OpenVPN.
- Killswitch với các tùy chọn có thể cấu hình cao (bật/tắt trên một số mạng nhất định, khi khởi động, v.v.)
- Máy khách VPN dễ sử dụng
- Hỗ trợ [IPv6](https://vi.wikipedia.org/wiki/IPv6). Chúng tôi hy vọng rằng các máy chủ sẽ cho phép kết nối đến qua IPv6 và cho phép bạn truy cập các dịch vụ được lưu trữ trên địa chỉ IPv6.
- Khả năng [chuyển tiếp cổng từ xa](https://en.wikipedia.org/wiki/Port_forwarding#Remote_port_forwarding) hỗ trợ tạo kết nối khi sử dụng phần mềm chia sẻ tệp P2P ([Mạng ngang hàng](https://vi.wikipedia.org/wiki/Mạng_ngang_hàng)) hoặc lưu trữ máy chủ (vd: Mumble).

### Sự riêng tư

Chúng tôi mong muốn các nhà cung cấp được đề xuất của chúng tôi thu thập càng ít dữ liệu càng tốt. Không thu thập thông tin cá nhân khi đăng ký và chấp nhận các hình thức thanh toán ẩn danh là bắt buộc.

**Điều kiện tối thiểu:**

- [Tiền điện tử ẩn danh](cryptocurrency.md) **hoặc** tùy chọn thanh toán bằng tiền mặt.
- Không cần thông tin cá nhân để đăng ký: Chỉ cần nhiều nhất là tên người dùng, mật khẩu và email.

**Trường hợp tốt nhất:**

- Chấp nhận nhiều [tùy chọn thanh toán ẩn danh](advanced/payments.md).
- Không thu thập thông tin cá nhân (tên người dùng được tạo tự động, không cần email, v.v.).

### Bảo mật

VPN sẽ trở nên vô nghĩa nếu nó thậm chí không thể cung cấp mức độ bảo mật thỏa đáng. Chúng tôi yêu cầu tất cả các nhà cung cấp được chúng tôi đề xuất phải tuân thủ các tiêu chuẩn bảo mật hiện tại cho kết nối OpenVPN của họ. Lý tưởng nhất là họ sẽ sử dụng nhiều chương trình mã hóa phù hợp hơn trong tương lai theo mặc định. Chúng tôi cũng yêu cầu một bên thứ ba độc lập kiểm tra tính bảo mật của nhà cung cấp, lý tưởng nhất là theo cách rất toàn diện và lặp lại (hàng năm).

**Điều kiện tối thiểu:**

- Chu trình mã hóa mạnh: OpenVPN với xác thực SHA-256; RSA-2048 hoặc chu trình mã hóa bắt tay tốt hơn; Mã hóa dữ liệu bằng AES-256-GCM hoặc AES-256-CBC.
- Chuyển tiếp bí mật.
- Kiểm tra bảo mật được công bố từ một công ty bên thứ ba có uy tín.

**Trường hợp tốt nhất:**

- Mã hóa mạnh nhất: RSA-4096.
- Chuyển tiếp bí mật.
- Kiểm tra bảo mật toàn diện được công bố từ một công ty thứ ba có uy tín.
- Bug-bounty programs and/or a coordinated vulnerability-disclosure process.

### Lòng tin

Bạn sẽ không tin tưởng giao tài chính của mình cho người giả mạo danh tính, vậy tại sao lại tin tưởng giao dữ liệu internet của bạn cho họ? Chúng tôi yêu cầu các nhà cung cấp được chúng tôi đề xuất phải công khai về chủ sở hữu hoặc lãnh đạo của họ. Chúng tôi cũng muốn thấy các báo cáo minh bạch thường xuyên, đặc biệt là về cách xử lý các yêu cầu của chính phủ.

**Điều kiện tối thiểu:**

- Công khai người lãnh đạo hoặc chủ sở hữu của họ trước công chúng.

**Trường hợp tốt nhất:**

- Công khai người lãnh đạo.
- Báo cáo minh bạch thường xuyên.

### Marketing

With the VPN providers we recommend we like to see responsible marketing.

**Điều kiện tối thiểu:**

- Must self-host analytics (i.e., no Google Analytics). The provider's site must also comply with [DNT (Do Not Track)](https://en.wikipedia.org/wiki/Do_Not_Track) for people who want to opt-out.

Must not have any marketing which is irresponsible:

- Making guarantees of protecting anonymity 100%. When someone makes a claim that something is 100% it means there is no certainty for failure. We know people can quite easily deanonymize themselves in a number of ways, e.g.:
    - Reusing personal information (e.g., email accounts, unique pseudonyms, etc.) that they accessed without anonymity software (Tor, VPN, etc.)
    - [Browser fingerprinting](https://en.wikipedia.org/wiki/Device_fingerprint#Browser_fingerprint)
- Claim that a single circuit VPN is "more anonymous" than Tor, which is a circuit of three or more hops that regularly changes.
- Use responsible language: i.e., it is okay to say that a VPN is "disconnected" or "not connected", however claiming that someone is "exposed", "vulnerable" or "compromised" is needless use of alarming language that may be incorrect. For example, that person might simply be on another VPN provider's service or using Tor.

**Trường hợp tốt nhất:**

Tiếp thị có trách nhiệm vừa mang tính giáo dục vừa hữu ích cho người tiêu dùng có thể bao gồm:

- So sánh chính xác khi nào nên sử dụng [Tor](tor.md).
- Trang web của nhà cung cấp VPN khả dụng trên [dịch vụ .onion](https://vi.wikipedia.org/wiki/.onion)

### Tính năng bổ sung

While not strictly requirements, there are some factors we looked into when determining which providers to recommend. These include content blocking functionality, warrant canaries, multihop connections, excellent customer support, the number of allowed simultaneous connections, etc.
