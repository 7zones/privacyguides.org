---
meta_title: "Mạng và trình duyệt Tor: Duyệt web ẩn danh - Privacy Guides"
title: "Mạng Tor"
icon: simple/torproject
description: Bảo vệ việc duyệt internet của bạn khỏi những con mắt tò mò bằng cách sử dụng mạng Tor, một mạng an toàn vượt qua kiểm duyệt.
cover: tor.webp
schema:
  - 
    "@context": http://schema.org
    "@type": SoftwareApplication
    name: Trình duyệt Tor
    image: /assets/img/browsers/tor.svg
    url: https://www.torproject.org
    sameAs: https://vi.wikipedia.org/wiki/Tor
    applicationCategory: Web Browser
    operatingSystem:
      - Windows
      - macOS
      - Linux
      - Android
    subjectOf:
      "@type": WebPage
      url: "./"
---

![Tor logo](assets/img/self-contained-networks/tor.svg){ align=right }

Mạng **Tor** là một nhóm các máy chủ do tình nguyện viên vận hành cho phép bạn kết nối miễn phí và cải thiện quyền riêng tư cũng như bảo mật của bạn trên Internet. Các cá nhân và tổ chức cũng có thể chia sẻ thông tin qua mạng Tor với các "dịch vụ ẩn .onion" mà không ảnh hưởng đến quyền riêng tư của họ. Vì lưu lượng truy cập Tor khó bị chặn và theo dõi nên Tor là một công cụ vượt qua kiểm duyệt hiệu quả.

[:octicons-home-16:](https://www.torproject.org){ .card-link title=Trang chủ }
[:simple-torbrowser:](http://2gzyxa5ihm7nsggfxnu52rck2vv4rvmdlkiu3zzui5du4xyclen53wid.onion){ .card-link title="Dịch vụ Onion" }
[:octicons-info-16:](https://tb-manual.torproject.org/){ .card-link title=Tài liệu}
[:octicons-code-16:](https://gitlab.torproject.org/tpo/core/tor){ .card-link title="Mã nguồn" }
[:octicons-heart-16:](https://donate.torproject.org/){ .card-link title=Đóng góp }

Tor hoạt động bằng cách định tuyến lưu lượng truy cập internet của bạn qua các máy chủ tình nguyện, thay vì tạo kết nối trực tiếp tới trang web mà bạn đang cố truy cập. Điều này làm lu mờ nơi xuất phát thực sự của lưu lượng truy cập, và không có máy chủ nào trong đường dẫn kết nối có thể nhìn thấy đường dẫn đầy đủ về nơi lưu lượng truy cập đến và đi, nghĩa là ngay cả các máy chủ bạn đang sử dụng để kết nối cũng không thể phá vỡ trạng thái ẩn danh của bạn.

[DTổng quan chi tiết về Tor :material-arrow-right-drop-circle:](advanced/tor-overview.md){ .md-button }

## Kết nối với Tor

!!! tip

    Trước khi kết nối với Tor, hãy đảm bảo rằng bạn đã đọc phần [tổng quan](advanced/tor-overview.md) về Tor là gì và cách kết nối với Tor một cách an toàn của chúng tôi. Chúng tôi thường khuyên bạn nên kết nối với Tor thông qua một [nhà cung cấp VPN](vpn.md) đáng tin cậy, nhưng bạn phải làm **đúng cách** để tránh bị giảm tính ẩn danh của mình.

Có nhiều cách khác nhau để kết nối với mạng Tor từ thiết bị của bạn, cách được sử dụng phổ biến nhất là **trình duyệt Tor**, một nhánh của Firefox được thiết kế để duyệt ẩn danh cho máy tính để bàn và Android.

Có một số ứng dụng tốt hơn một số khác, và một lần nữa việc đưa ra quyết định tùy thuộc vào mô hình mối đe dọa của bạn. Nếu bạn là người dùng Tor thông thường và không lo lắng về việc ISP thu thập bằng chứng chống lại bạn thì việc sử dụng các ứng dụng như [Orbot](#orbot) hoặc ứng dụng trình duyệt di động để truy cập mạng Tor có lẽ là điều ổn. Increasing the number of people who use Tor on an everyday basis helps reduce the bad stigma of Tor, and lowers the quality of "lists of Tor users" that ISPs and governments may compile.

Nếu điều tối quan trọng với bạn là việc ẩn danh hoàn toàn, thì bạn **chỉ** nên sử dụng trình duyệt Tor cho máy tính, lý tưởng nhất là trong cấu hình [Whonix](desktop.md#whonix) + [Qubes](desktop.md#qubes-os). Mobile browsers are less common on Tor (and more fingerprintable as a result), and other configurations are not as rigorously tested against deanonymization.

### Trình duyệt Tor

!!! recommendation

    ![Tor Browser logo](assets/img/browsers/tor.svg){ align=right }

    **Tor Browser** is the choice if you need anonymity, as it provides you with access to the Tor network and bridges, and it includes default settings and extensions that are automatically configured by the default security levels: *Standard*, *Safer* and *Safest*.

    [:octicons-home-16: Homepage](https://www.torproject.org){ .md-button .md-button--primary }
    [:simple-torbrowser:](http://2gzyxa5ihm7nsggfxnu52rck2vv4rvmdlkiu3zzui5du4xyclen53wid.onion){ .card-link title="Dịch vụ Onion" }
    [:octicons-info-16:](https://tb-manual.torproject.org/){ .card-link title=Tài liệu }
    [:octicons-code-16:](https://gitlab.torproject.org/tpo/applications/tor-browser){ .card-link title="Mã nguồn" }
    [:octicons-heart-16:](https://donate.torproject.org/){ .card-link title=Đóng góp }

    ??? downloads

        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=org.torproject.torbrowser)
        - [:simple-android: Android](https://www.torproject.org/download/#android)
        - [:simple-windows11: Windows](https://www.torproject.org/download/)
        - [:simple-apple: macOS](https://www.torproject.org/download/)
        - [:simple-linux: Linux](https://www.torproject.org/download/)

!!! danger

    You should **never** install any additional extensions on Tor Browser or edit `about:config` settings, including the ones we suggest for Firefox. Browser extensions and non-standard settings make you stand out from others on the Tor network, thus making your browser easier to [fingerprint](https://support.torproject.org/glossary/browser-fingerprinting).

The Tor Browser is designed to prevent fingerprinting, or identifying you based on your browser configuration. Therefore, it is imperative that you do **not** modify the browser beyond the default [security levels](https://tb-manual.torproject.org/security-settings/).

In addition to installing Tor Browser on your computer directly, there are also operating systems designed specifically to connect to the Tor network such as [Whonix](desktop.md#whonix) on [Qubes OS](desktop.md#qubes-os), which provide even greater security and protections than the standard Tor Browser alone.

### Orbot

!!! recommendation

    ![Orbot logo](assets/img/self-contained-networks/orbot.svg){ align=right }

    **Orbot** is a free Tor VPN for smartphones which routes traffic from any app on your device through the Tor network.

    [:octicons-home-16: Homepage](https://orbot.app/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://orbot.app/privacy-policy){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://orbot.app/faqs){ .card-link title=Tài liệu}
    [:octicons-code-16:](https://orbot.app/code){ .card-link title="Mã nguồn" }
    [:octicons-heart-16:](https://orbot.app/donate){ .card-link title=Đóng góp }

    ??? downloads

        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=org.torproject.android)
        - [:simple-appstore: App Store](https://apps.apple.com/us/app/orbot/id1609461599)
        - [:simple-github: GitHub](https://github.com/guardianproject/orbot/releases)

We previously recommended enabling the *Isolate Destination Address* preference in Orbot settings. While this setting can theoretically improve privacy by enforcing the use of a different circuit for each IP address you connect to, it doesn't provide a practical advantage for most applications (especially web browsing), can come with a significant performance penalty, and increases the load on the Tor network. We no longer recommend adjusting this setting from its default value unless you know you need to.[^1]

!!! tip "Tips for Android"

    Orbot can proxy individual apps if they support SOCKS or HTTP proxying. It can also proxy all your network connections using [VpnService](https://developer.android.com/reference/android/net/VpnService) and can be used with the VPN killswitch in :gear: **Settings** → **Network & internet** → **VPN** → :gear: → **Block connections without VPN**.

    Orbot is often outdated on the Guardian Project's [F-Droid repository](https://guardianproject.info/fdroid) and [Google Play](https://play.google.com/store/apps/details?id=org.torproject.android), so consider downloading directly from the [GitHub repository](https://github.com/guardianproject/orbot/releases) instead.

    All versions are signed using the same signature so they should be compatible with each other.

### Onion Browser

!!! recommendation

    ![Onion Browser logo](assets/img/self-contained-networks/onion_browser.svg){ align=right }

    **Onion Browser** is an open-source browser that lets you browse the web anonymously over the Tor network on iOS devices and is endorsed by the [Tor Project](https://support.torproject.org/glossary/onion-browser/).

    [:octicons-home-16: Homepage](https://onionbrowser.com){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://onionbrowser.com/privacy-policy){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://onionbrowser.com/faqs){ .card-link title=Tài liệu}
    [:octicons-code-16:](https://github.com/OnionBrowser/OnionBrowser){ .card-link title="Mã nguồn" }
    [:octicons-heart-16:](https://onionbrowser.com/donate){ .card-link title=Đóng góp }

    ??? downloads

        - [:simple-appstore: App Store](https://apps.apple.com/app/id519296448)

## Relays and Bridges

### Snowflake

!!! recommendation

    ![Snowflake logo](assets/img/browsers/snowflake.svg#only-light){ align=right }
    ![Snowflake logo](assets/img/browsers/snowflake-dark.svg#only-dark){ align=right }

    **Snowflake** allows you to donate bandwidth to the Tor Project by operating a "Snowflake proxy" within your browser.

    People who are censored can use Snowflake proxies to connect to the Tor network. Snowflake is a great way to contribute to the network even if you don't have the technical know-how to run a Tor relay or bridge.

    [:octicons-home-16: Homepage](https://snowflake.torproject.org/){ .md-button .md-button--primary }
    [:octicons-info-16:](https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/snowflake/-/wikis/Technical%20Overview){ .card-link title=Tài liệu}
    [:octicons-code-16:](https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/snowflake){ .card-link title="Mã nguồn" }
    [:octicons-heart-16:](https://donate.torproject.org/){ .card-link title=Đóng góp }

You can enable Snowflake in your browser by opening it in another tab and turning the switch on. You can leave it running in the background while you browse to contribute your connection. We don't recommend installing Snowflake as a browser extension; adding third-party extensions can increase your attack surface.

[Run Snowflake in your Browser :material-arrow-right-drop-circle:](https://snowflake.torproject.org/embed.html){ .md-button }

Snowflake does not increase your privacy in any way, nor is it used to connect to the Tor network within your personal browser. However, if your internet connection is uncensored, you should consider running it to help people in censored networks achieve better privacy themselves. There is no need to worry about which websites people are accessing through your proxy—their visible browsing IP address will match their Tor exit node, not yours.

Running a Snowflake proxy is low-risk, even moreso than running a Tor relay or bridge which are already not particularly risky endeavours. However, it does still proxy traffic through your network which can be impactful in some ways, especially if your network is bandwidth-limited. Make sure you understand [how Snowflake works](https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/snowflake/-/wikis/home) before deciding whether to run a proxy.

[^1]: The `IsolateDestAddr` setting is discussed on the [Tor mailing list](https://lists.torproject.org/pipermail/tor-talk/2012-May/024403.html) and [Whonix's Stream Isolation Tài liệu](https://www.whonix.org/wiki/Stream_Isolation), where both projects suggest that it is usually not a good approach for most people.
