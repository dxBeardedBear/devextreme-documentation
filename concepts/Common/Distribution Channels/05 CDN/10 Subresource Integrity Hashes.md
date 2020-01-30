You can use <a href="https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity" target="_blank">Subresource Integrity</a> (SRI) hashes to verify DevExtreme files when fetching them from CDN. Each link below contains `sha384` and `sha512` hashes:

---
##### 20.1.0

    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx-diagram.js" integrity="sha384-Da/PVfYFnOfOqvwCcCAcwpzPND5GjABGuGACbe9TLrEXojt2AN/ZgCB02u3LVPo8 sha512-ms/6kaYeQQRTSYMrvCiSDGwz+O3wmwm+lP2dFULgzpDPJk0+SO40O+b3ZCwZlhoGdPoO3Z8vFHU8GlOG3jjuJA==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx-diagram.min.js" integrity="sha384-Z+L90e/bIm1JDkfl8Pr/RoS9PprSZMTmFy/wtGRWdqzqADgWbyyFmi8oMdbxK9w2 sha512-sATNsHIC9CICj7R7EA9wBRBox8n3uBuhq6i2I4D1kVb2nf1PNqMfnLxvxWUD0fqKCoHQawSuQM3vY1uA+oDUkw==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx-gantt.js" integrity="sha384-eE/Se4zcnVtqMR9+VmvynCDdTFioEnCdJLCdF1DjkKR6sm3HMIlbhjSoCNLA7s07 sha512-yArW17sreCZjpWW2yCkTRWdpqi1RCbrCvSovnZyhA9w2rgE/TOyTiQwkvGNEoTokBgDWbToUI/2mkgIsa2Feuw==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx-gantt.min.js" integrity="sha384-wMQRV2z4WGB197j1cyxTLWtAHIQM/zrQdaDcVExCV+cudeO4xaXIXyFoOSYcWgbz sha512-bvUvnaoG9jWrWV2m9drCoBm7Th2iuDjGQvN9ECv0ZR5TrWSE9h3kYBWulWiroGIFEdU8ryIcmS0Xh1PJmOygqQ==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.all.debug.js" integrity="sha384-Ea/ZTSkiQQ+QGdHF32dtB4HkBHHtuTXf3h7owsDQLJTHl+a5vTz6So5CH4rpF9b5 sha512-Ocujx2hQVdGsbtJsgMHMWajHPJV+q0y0h/UxiyC6mJTVOyUkH6XoexpZYKddN9A3Npxt1naEcTxzOwSy/Sml+A==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.all.js" integrity="sha384-R8i8zRU3W7btxGtXnThzazPMjf7U9awTaikfvweImcBsggyVwi+9ih400a4+Ku/d sha512-GOpyUDjWqmBKfWJgNMriOKAHyqMx6p5U0IlJxf+UNgUxBY92R1XP9jGaf7/9xKdpvutpv6CoSK7MSUcfJMbGxg==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.aspnet.mvc.js" integrity="sha384-53Kx0QOiiep1hjnaIIsabdNL/DQVHaJ2Gz9XQf4UP0gSO5aRGIrUhf4G0ctlD3gD sha512-jPCOMKSUUhOVxJPxLAfLSpJAUofPESXMhahpXwx+G0nCd1O8StPLynX4RY+Hx6RPMAYQiginMmgXEYkudg0uiQ==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.viz-web.debug.js" integrity="sha384-Hpi+0fBn+zF2arNwwkWymUFcFs+uA9CmuIkHK5iv5THelmDPdRFGoYhjPGm3e1pe sha512-RqdhxGmozI4Fb/z/lrGAJeC32OoBXUFSPHOv+1zT0IMUR+UaQjVTuFHn+UC/yf1hnMUmBohwe91xnb+cPZiSEg==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.viz-web.js" integrity="sha384-Ly7SMOnQ/5sl8XE2k2/LPKQV0us83TRvPFanbwcZKfRZH8ZiJwHuwDrmdO6DuOej sha512-eaahysKWXWwQTAwIAHv3Y80Jm7Hgxlf6xd41KrAIcsp95+/EgAxRKa6WFQXCMB8hgnRNqkAQRLtP6+QraTIQ0Q==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.viz.debug.js" integrity="sha384-1MKF1C3fanJAaMyBEwXJUyQ+ci1Eycf/eSz3miX/uYbkx3nxYYFPhVqjvd+uWQVN sha512-xtA5fldEy1wlMF+GEsvUExHbsKviJwxhnMlX8fM2XnF0fE4V992AaDVFys9vK5hyoevQf24HAuNdTBClFrJhlA==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.viz.js" integrity="sha384-apzLgftpu40gvNPWMOmZE1wPerLXb9+gri11Sezpj88AxeuyJaqb+yyr5shtanIv sha512-uavLdZNp4myvz/vkUZN19xRdx4SVpyxZ1/nJG18jA+0ASsAepD4LJDP4gAgAY+PjiaIYorE4nlxAE6z66UR9AA==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.web.debug.js" integrity="sha384-zD7dt3xaWhGTa6uGKAcsckeH65sK6Sxphr3vxepjgW01ywOJGMN0MJqzAq07Tk7E sha512-AKirG0mHHaYMbREAUpGhxrUqDiR7M2TtRWqov0sEuEd9KE503TEG5yLq7waa9eD8B+HYPYoVRKSfYckk8O/TjA==" crossorigin="anonymous"></script>
    <script src="https://cdn3.devexpress.com/jslib/20.1.0/js/dx.web.js" integrity="sha384-yio/wsz7pyxgFl/gW0gpqOGRKRGp1ipv+2jvsiPZNj+xNxNLBoR3Spp/U75u3SfN sha512-ltQIy2H6/DAdIfDRJQl9i5y4QxetvgSX83C8V3ZbYgQh0qfxnBKN2yJoTPO4blMu/XTUAAEMto5ogPCIqiyQSQ==" crossorigin="anonymous"></script>
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx-diagram.css" rel="stylesheet" integrity="sha384-ApoIPuZW5Un3tkdiXu7zn/mShd7VC8V2dvChzc/RoqhjfRnlEccjHpBgWGWNi9Xm sha512-5OfXaCipq1y96jkuF3GSyen61qaKlFacygYZfPZyhUnWmtndyUDpO6GHGSzCeUSWJwI8POWNfyrDv625tqILtw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx-diagram.min.css" rel="stylesheet" integrity="sha384-eSwmh4OjzpcEPLZ0WILoKJU/j0k3yovLSjtGcfC3eP4dgYjslQEMViysXC3UDdbI sha512-QAKUyt1IAa0ghx/sF7oXRUrPFePSIylsofovx+lLZI6VHO34Xzox2p4P0UMdeljVBmOnjJpRkZMK85JSLhnTCA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx-gantt.css" rel="stylesheet" integrity="sha384-Gyq1Cs4KW7bVzqUIH6TfaUwEJe/SZ/DTjIzcsxh6H9JQwQVerVhBlzsiOwyG/I3t sha512-Z1rfWnv+Zwcx71fLu+p2UWnusOnTNwOOYrgIuCTkR9qH/N8p8NEO+lMWj9xCLnHtBsMIH98fO5nS6fWGdRbuHQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx-gantt.min.css" rel="stylesheet" integrity="sha384-wx9BReHbFaMivTzYNxKuXWLNREjfNMaHFcNvuKIHLfGVmY5Qll3kw36XFiYvx7qf sha512-Ndony3Utgmugv8TFhiMBAOavAe3vDP2T4J9VEsPT1fDrLKgQ0MNFqRDC81CrGY/EPWU8ynsWMXyzg8aLujWDPw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.carmine.compact.css" rel="stylesheet" integrity="sha384-2f8ZBdcK6O6CPoPAMNYRaK0tolpBkf9y9GJLirgeysOBtUa1y92fBuIxyAXaUzue sha512-CWzEDFNFA5J0T/kPteDC7dxhwxz0dKNnKhHfQdfJTRZvhZzxCnicKjH3HoYzRw/BmCWPRc5xaICDrcTBUl2fiA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.carmine.css" rel="stylesheet" integrity="sha384-W3JxtBImuzQ54DaF1SS+RWHpJSsRhQND4XMQmY2YzXSVYKkEkTVA7TfayTVJ50ab sha512-+KiWn5wdTPCpbZNrp/XRhT+tETt5/2BgJOryDwDR6LoF6tcfCNOeDA3hK/lWO5/qdUvl5RCzslsFYIl+tb0yqw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.common.css" rel="stylesheet" integrity="sha384-N/ylvTwyXoL5J8qlYlMuo6DrfyIz9ESEfvTMsMDLbBhNvslaZHVFEnPdgsDM4e5b sha512-lVx4/+lWFK9oOs4mp6KL00v94ppzk+9cN1RULzboI51WEOmA+qEbmWQdXOv5Df1Ta1QhatV1asGCp556aWEFTQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.contrast.compact.css" rel="stylesheet" integrity="sha384-GxltQkh+4Xc7+FPcu+e2ObCdbv+gwG6ZghMoaPvs/UdxisNJwtn9qDnxaHbC0z5C sha512-mBM2DP6oLfrmEQEDcrEw1f2j6ZcknzKUq7AJRyWruJi6ARILoD6lC7qrspaHzdtSNJVQ3bKwcr7jyJKyvcZB9w==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.contrast.css" rel="stylesheet" integrity="sha384-VSRKYms0/Q7PHyo1BLfMhM1bnEQ3QedDR2B2LhVexNtGbFS3VfZAIHS6HamOcb32 sha512-FT4OlDFvzM4n4tyqr8uJKvIL5hPKwXztP9VFmzjaSR1mCgiNbO326NmkYBaiqorFaz0LojgfqFT8HYTafR/9Pw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.dark.compact.css" rel="stylesheet" integrity="sha384-6Re7UlFdjnXfSkYmhkhTOTJVU2XEBgTiTKxgpKNCf7AuL9v3WhtGfDV89rzv1Bap sha512-xAm0HZFM//FKOqnm6sjmMELUWpIAt3IHCvo5lsIdB0aqDSKMTeR1a9WpJxevY5FuODa82DX95R6p+WkAzndBmw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.dark.css" rel="stylesheet" integrity="sha384-ORCF2rksLRKEr0jUq/aH+iHPtWzq6lCV3oTCLqmP0BT7WgwdNPxoDuN2WEkakLF4 sha512-h394z18Yz8YI51201VKhqfiqmNDqTUN75oplCPng7T9l7vPoP/0HHOONSFFMzRN9Jo6npFCdwpcwAY0HzWuzbg==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.darkmoon.compact.css" rel="stylesheet" integrity="sha384-GAurCXelqWWtBfIzxBY+m3ldi5vaLO3PRrDVbCiSjMvtN/sY/f47M08iGpQ/kSHZ sha512-lfE1/kQtKHoUfIMgTGpR4CXX4zKxVhPp0b0XllA/Fxc0RlyjbR3OdZNRfBCCsQfmlsNN4blW69KVS1zjT2E7cw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.darkmoon.css" rel="stylesheet" integrity="sha384-8HiY2uEd+VA7L3kZ4yXyioVrEJT8TG+fSkhG8jUSJkr7DDm32kjsC0kB11xZ8Vzw sha512-kkXtNB1QwdU2iOJ7SFMZOH+vXCXI0yE/k1vBQTvz9v666AjYh3dEHmv2Z2aQaov3J8YKlY2L/WBlLHdwKzGfHQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.darkviolet.compact.css" rel="stylesheet" integrity="sha384-MXADLTLcgM9Y4oiNnCY3Zqc8yFGObEA1iyj0CbClbZEEEtXmFSQ8/OwDCJKKh5Fp sha512-NKU36iyHcSZdWgm5fKMaW01wZV6frxg9HDTM878+ktU3bxNBbFlhJ1dOPwepnz30S6IsJs8pxkTsxAVDLpzsWw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.darkviolet.css" rel="stylesheet" integrity="sha384-QwbbBr7FFn2OIYXI84bpsMuzBtx+OBqGzgvw5KTNABdHSNemVfMFC4Zx9SI4y6Ao sha512-kp7gbYFpYHf0AOva0ffOtlp1snCzjJQJa8+asWNNA2jhLZ21OJp8oIaMxrF+EPs8zBS3WK6JDZGZiE9tLgtclw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.greenmist.compact.css" rel="stylesheet" integrity="sha384-/b3bmFFPoFAFQGL/3cHI53vfZhoWcv4HJD/IufBE6HyIBFMLzw0YdRpjksee+MR8 sha512-km/azh0fhBpzWRR7LsZzV/YtK4vLG2GnpzZXeqqj1p6TEef4kKDy3yuy6gcuo9xj+ICbk8srmsIZGU7dXHjW3Q==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.greenmist.css" rel="stylesheet" integrity="sha384-GaIwjM9LD5f+aR/nJCF1gMxq/Qv0iyh/p29gjgNInFTdbOiJtbn2CvuCgyUjnRhK sha512-x4dFJpwLWDHES33j+ah4ChPlDSLkdaOgdo76suid9/DqovkUit5DxJUVz0vRIPFqcSSKg5UbquCmaoF4pPSp8A==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.ios7.default.css" rel="stylesheet" integrity="sha384-krw6Vr1iJANxj+9Tp+2cmFCSbu3CCnMymXqmAgoq9s/MERiaP2Oq5oLnKJDvubpe sha512-viMhKjD9YP1r4fgmjEenJv6SeCHJwzDUi9E8Rt7jOr3K2NGRTUV32bxoBWSO4DcvO7zQguOyKfvF1myThxHp8Q==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.light.compact.css" rel="stylesheet" integrity="sha384-TS3WTMQO5Mc9E0lJywww4qzwnLpvJMQoxf0VEle7DAKVIneuTycNYgafMu52j01l sha512-spniYU1ctCMw8FVu/So44WoRAKxph7aWKSyCi59yk5W+DDLjQ4PSKofEUjbsRodueOSdhNYs8pbLg1xQR1MxZQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.light.css" rel="stylesheet" integrity="sha384-3xN1Nyzt+xoOnORRorXKOrK8RRujowlO0JvRsDdvNan8AUJXM+Sv+jQ2rVZxeBZM sha512-mGdZZtByxytfDqJqm/HGaojoaZo5PAvjVpXME+X7MvwRrwiTNOk5gd0HdrUKP5zDL1RnLXmdAfUdrN47vWBhDg==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.blue.dark.compact.css" rel="stylesheet" integrity="sha384-K3O//DTkkHNEKcPKgP1UiiDP/RHNit6qc+DagCtcND1e3CexhOxe27QRbROFdFlM sha512-QrgYRJ3HdbAeMCdmLlUbSPDpGoQxyuMElRCbGzgiEoxaa7fb27MzCHZgbb1n2H0sNiCJvnpv5sWEnf0CGkGVlw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.blue.dark.css" rel="stylesheet" integrity="sha384-ASKYn+xwsxLdYHYMYylZOifkvqn3Y2sEQ1lopvx5m5Hg/9NhKmzfIL+lNOMPDIIw sha512-IG3cwYnIH9POYtZwvVFhyEeNUvGSRH0m5UoEfsRfvXwuXKa0snQOYjupK5U/OmnYbnYMku3iboF7FUOr/sE1Wg==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.blue.light.compact.css" rel="stylesheet" integrity="sha384-9kky6yTJRDuVOrWQtlQ+sDmujAGKM4PiNX107DmDzohJtFmUngWSi+4MYPvDI2Ia sha512-DOsZ3bU+Kuvo+ZfUDEHobNZmkgmtDavltM/eciyCIavJdkcR1ICfDdBFtWoj38A/QdrgcwzoqpLlXpS3qPzSBA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.blue.light.css" rel="stylesheet" integrity="sha384-bc0L0g5jG4eO3D0YmsRer+VvwDeK5PXgj6sMk6BB7eM1D4Duv+Wuty8k6uT6Yoqj sha512-Ro5i99o/O9fjnvzOOaHRk53X4G65vEO9mphJxRRmkUuVfiC3u5qrMxnHHF03GiIqVi/DRvPiVyuTURHBzPIXEQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.lime.dark.compact.css" rel="stylesheet" integrity="sha384-qpK+9lKIUjF98021HSNJvPii5/ILiD6lQW8uFYkavfeiR2sz2zwWldT4JGfUAIWw sha512-Kw6AemJU/WOV6ntDRo7i8bYfJjxIZ+EgEgfiDG2I5Z/cB3vTEZSuZoBuAusQUexJYIYNJPm0Eh+ZwKIGz32etw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.lime.dark.css" rel="stylesheet" integrity="sha384-EbKMbjwEzuPlx6zWmc50dKR1x5QYl6v66TLnhc0wZKaBI3OZ4ZasYCSiXFg+R/2s sha512-dj4l81llaoDsSXGrTMVZcFX+yvOMb9T13Q9mG/YtV6knDPeVA7EtKc4XQNtuDvqtgXx7lN7WyiljXD2BFX8L6A==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.lime.light.compact.css" rel="stylesheet" integrity="sha384-6DLefcJEJShGxMi1N161XWEqNIclrV3zou0AbE7Dwuhtfd0mK/C5yb/KPpsz1iau sha512-4+P6brrfZOTPBngNNCMHRkQvcnHi9BTkr59XDUf2PBnQ8yhVGSXFaAnNP04fMDUiB17PcYXBfQSOPKpRsbGgvA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.lime.light.css" rel="stylesheet" integrity="sha384-YUGdQDU3JcSYe08AZBoCZViDhvJLHV9GtSXJkhpRViRoml+yDhNOdLhagQzxyRvV sha512-WvklwIQ74q+NtGegoSP/vd3om5PORDNYAuTxPbaNYNrIgeqsoMnvlMQcrQ1mt5U7mNlvCWrC8g8o9+B51XpSfQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.orange.dark.compact.css" rel="stylesheet" integrity="sha384-R5oLngbqB6Cytv3PTDwJKL3G2GvbNp//XJUvcTSXD8WTtxhjbYkvA4czOroqrS4N sha512-cZAkgjgFENZerNNr6hbOXPakY36n/83C+BaVtG5r7wC0IFncFvg2oG2FvRM7zuuoE8cKFkHP1s3w05JbxKd5kA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.orange.dark.css" rel="stylesheet" integrity="sha384-mAhmDzFmJu80hD73zZwM4Jp47MDksZk1uUoqejKEn+cdb+RNFCsD4CSI1n03DAdE sha512-poLPBGxNgz3/I1Gks/LE6FxVTBA08xPWhtB80eojg0xqvAoZr7pOGUr7+PPkuJA+Tk4wrqwtzCtSGhwGON9JPA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.orange.light.compact.css" rel="stylesheet" integrity="sha384-I5R6rMipnwvQSeoC3TMz0gPu+znEiZmmhqYFaAdosVJHKXSkavwJcfGcsf152KZX sha512-pOik4IP3RQKKk71wCFAWOa8l5SipONh3xRJj2yeceMKpvUfCyzdQG/YZi8F4CuE93yEpyEUfgnU2L6A84VimAw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.orange.light.css" rel="stylesheet" integrity="sha384-K7nhlkGKM5bIYgEvky1iMbsn3ioFcFRgt6Nw2l+QBEaY/G/WVtv3cY/+KVPvywv/ sha512-WZhP3KkeH331Vj61QJvMg5vFVg1nFfwhRK7xq48QxMowPgA3rfkHCFcnTzv9zC9g1tWgLgwIsPsa7gnbEwMaNA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.purple.dark.compact.css" rel="stylesheet" integrity="sha384-tyldEG0a15ISefaLmKKNAfzY5RafUFBTwjw40U6BB78fErBccp7hevFYDCBb7OV2 sha512-B7wALy2mKXUGv5YV1SFa20oCI4TYkXWOnSjtwQEa3t+riDZf8wcTDZ74VLmPq2W/OlriuQSaS82gQlwZNVlMMw==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.purple.dark.css" rel="stylesheet" integrity="sha384-WHOi12F3m4cD/7RcDjB0JUtmc7TdlvkWSYYXvN4O6QKQocsUUQpvilAhLMO0t9QU sha512-irRWdB/WZU5rlrolq7HAWy99Sa0w0AgzieETyVoDQtzQdlNeaW9WaRZ4M2znXNmWvkCiZZ9uut3huMi3q2s4bA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.purple.light.compact.css" rel="stylesheet" integrity="sha384-KUJqNiwW20VLhK72vENSgjb2+KM+4BfCpM2v587NzlHgPrdW5Mcif0hMgT9f56MC sha512-+iRVfZvdCaQPVRwJqJwa5L0Ng6UyQmHss8WUUYaXsFmyOV/Hf45jEmeV0BOjONYqHQosDPgoed9FuuFgZXHpJQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.purple.light.css" rel="stylesheet" integrity="sha384-4amL5c5sGZrzZM03okT6FwtRd7tTVOe3B2byXnF5gZeGezVfg1A5cQND+6Jj2hGk sha512-sGL3n1b8sub/0vTelxy/2KbZiHAJOcxFmAyOT3cMo3sIM4rO4JvkEBDQ6M1EMwDld/GxeY1sBXa9AR+OTSHDOA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.teal.dark.compact.css" rel="stylesheet" integrity="sha384-+8d+YoSEEhxYr2DKt6Z28miswBNKcTFy4RVnElPCksJwSjWBHYxPwFdRyHJ6qmCi sha512-9w3Z5rCF6x1vk504J07QyQfOZA2lrlsCtgxj8d33sWmz9ZlMYyJFRRWxo77ZnQHAPMMNmXcDPT6rzhslJwmVAA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.teal.dark.css" rel="stylesheet" integrity="sha384-EKbSPxSZnhnlwtY0lzWVLaYNhy9akpuD7r7X7i9OgKjzdeJ4yicg0tMUxlp06Tw/ sha512-pHbSCkxU3LPvQjN8wSFE5izcxpoeTYuPop4ljpoX6AAHeXWulWUZftt3EiP5TGrLEDW24TzcfE6yBS9crNf5qQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.teal.light.compact.css" rel="stylesheet" integrity="sha384-xhXmjSKKltheGNQmb6OP6Z8l89x7wr//TGtLFRX35nAQzq4Ad9nNzt1P64XHnBzi sha512-ySJkQtcwchZCGsUqlSZ/IAY/HhJOc168ERc6GtyEnURkaa4VEhdqRN+2V5BCiXQGqApfv6WBuFxclrJErBzN8A==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.material.teal.light.css" rel="stylesheet" integrity="sha384-2BPz6N0TR+kAW/E1Zv1wKG7miurQGBmaNh1/B1wM/t3fTPZApi6KCQicDk24yAgJ sha512-QkIdYjw5gsx70LFljlvdkXFkpQc5uKcAIq4vySRGaM66OzIuBuTTnMWL4gTtJ/iQcII3sHCn13WKc35Q8YABbQ==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.softblue.compact.css" rel="stylesheet" integrity="sha384-AiMMVGJ6vJso4Ki4WbcSkj0jM2l6ijOkmlT+AqhMdZuIxYNg+OzRtVLs7n/b0drf sha512-p+2cEIzlhjUMF2XrfcfR2VzXVTqpYa8FWd72yJToEGExC+4dBEKu/niPiujuBW8Mb5fI45eMbiGGal7WgLDHMA==" crossorigin="anonymous">
    <link href="https://cdn3.devexpress.com/jslib/20.1.0/css/dx.softblue.css" rel="stylesheet" integrity="sha384-QwBeikfwNzep5CIoSwCaX0xZni42QWNrBjIBSbkH1txCEd0vKTFp9FLU95VjH7pW sha512-RVMfh2pbCLDUdTdedTwMlQe+kMbSzXcHl0V7WXcvy8RKHskobcrT3xlBRCETsJkHY6lmiA1yRo/AZ8h1byLy0Q==" crossorigin="anonymous">


---