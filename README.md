
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">

<head>
    <meta name="google-adsense-account" content="ca-pub-5760475094470696">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>DarkSSH - Premium SSH SSL, and OpenVPN Tunneling Server</title>
    <link
        href='https://darkssh.com/images/1648793834_favicon_darkssh.png'
        rel='icon' type='image/x-icon' />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://darkssh.com/themes/plugins/flag-icon/css/flag-icon.min.css">
    <link rel="stylesheet" href="https://darkssh.com/assets/css/app.css?id=6754b3a5f094e7d5f787da96f55e3d3a">
    <link rel="stylesheet" href="https://darkssh.com/assets/css/custom.css">
    <meta name="description" content="Darkssh server, Free SSH and VPN accounts, SSH Tunnel, OpenVPN, V2ray Server, TrojanVPN, Shadowsocks, WireGuard, Secure internet browsing, Darkssh for free ">
    <meta name="keywords" content="ssh account, ssh ssl account, free ssh, v2ray server, ssh udp, ssh websocket, v2ray account">

    <link href="https://darkssh.com" hreflang="x-default" rel="alternate" />
    <meta content="ZYn-kuiRS0HjRvOmreRZMhO3drmV4t6BAUGr3-I93Gk" name="google-site-verification" />
    <meta content="Indonesia" name="geo.placename" />
    <meta content="Administrator" name="Author" />
    <meta content="general" name="rating" />
    <meta content="id" name="geo.country" />
    <!-- [ Social Media meta tag ] -->
    <meta content="DarkSSH - Premium SSH SSL, and OpenVPN Tunneling Server" property="og:title" />
    <meta content="website" property="og:type" />
    <meta content="https://darkssh.com" property="og:url" />
    <meta content="Darkssh server, Free SSH and VPN accounts, SSH Tunnel, OpenVPN, V2ray Server, TrojanVPN, Shadowsocks, WireGuard, Secure internet browsing, Darkssh for free " property="og:description" />
    <meta content="DarkSSH" property="og:site_name" />
    <meta content="en_US" property="og:locale" />
    <meta content="en_GB" property="og:locale:alternate" />
    <meta content="id_ID" property="og:locale:alternate" />
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5760475094470696"
     crossorigin="anonymous"></script>
    <script src="https://darkssh.com/assets/js/app.js?id=346467b23c2587458e0d465da4df850a" defer></script>
</head>

<body class="font-sans leading-normal text-standard-origin bg-body mx-6">
    <header class="header pt-8">
        <div class="container max-w-screen-xl mx-auto">
            <div x-data="{ navOpen: false }" class="flex flex-wrap justify-between">
                <a href="https://darkssh.com" class="inline-block self-center">
                                            <img src="https://darkssh.com/images/1648565419_logo.svg" class="w-48"
                            alt="Logo">
                                    </a>
                <button x-on:click.prevent="navOpen = !navOpen"
                    class="inline-flex lg:hidden w-8 h-6 flex-col justify-between self-center">
                    <span class="block w-full h-0.5 rounded-md bg-gray-200 relative top-0 duration-200"
                        :class="{ 'rotate-45 !top-[12px]': navOpen }"></span>
                    <span class="block w-full h-0.5 rounded-md bg-gray-200 duration-100"
                        :class="{ 'opacity-0': navOpen }"></span>
                    <span class="block w-full h-0.5 rounded-md bg-gray-200 relative -top-0 duration-200"
                        :class="{ '-rotate-45 !-top-[10px]': navOpen }"></span>
                </button>
                <nav x-show="navOpen" x-on:click.away="navOpen = false" x-transition
                    class="lg:!flex py-4 mt-4 lg:py-0 lg:mt-0 rounded lg:bg-transparent bg-secondary bg-opacity-30 w-full lg:w-auto items-center">
                    <div class="mx-4">
                        <a href="https://darkssh.com"
                            class="lg:w-auto w-full inline-block font-medium text-lg text-white">Home</a>
                    </div>

                    <div class="mx-4 py-2 lg:py-0 relative" x-data="dropdown"
                        x-on:keydown.escape.prevent.stop="close($refs.button)"
                        x-on:focusin.window="! $refs.panel.contains($event.target) && close()">
                        <button x-on:click="toggle()" type="button" x-ref="button"
                            class="lg:w-auto w-full font-medium text-lg flex items-center text-gray-200">
                            SSH & OVPN
                            <svg class="ml-2" width="12" height="12" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M6 10a.996.996 0 0 1-.707-.293l-5-5a1 1 0 1 1 1.414-1.414L6 7.587l4.294-4.293a1 1 0 1 1 1.414 1.414l-5 5A.997.997 0 0 1 6 10Z"
                                    fill="#E4E4E4" />
                            </svg>
                        </button>
                        <div x-ref="panel" x-show="open" x-transition.origin.top.left
                            x-on:click.outside="close($refs.button)" style="display: none;"
                            class="lg:absolute lg:w-48 w-full z-10 bg-white text-gray-600 py-2 top-auto mt-4 rounded">
                            <a href="https://darkssh.com/server/SSH"
                                class="block px-3 py-2 hover:bg-gray-200">SSH Server</a>
                            <a href="https://darkssh.com/server/UDP"
                                class="block px-3 py-2 hover:bg-gray-200">SSH UDP</a>
                            <a href="https://darkssh.com/server/Slowdns"
                                class="block px-3 py-2 hover:bg-gray-200">SSH SlowDNS</a>
                            <a href="https://darkssh.com/server/OpenVPN"
                                class="block px-3 py-2 hover:bg-gray-200">OpenVPN</a>
                        </div>
                    </div>
                    <div class="mx-4 py-2 lg:py-0 relative" x-data="dropdown"
                        x-on:keydown.escape.prevent.stop="close($refs.button)"
                        x-on:focusin.window="! $refs.panel.contains($event.target) && close()">
                        <button x-on:click="toggle()" type="button" x-ref="button"
                            class="lg:w-auto w-full font-medium text-lg flex items-center text-gray-200">
                            V2Ray & Xray
                            <svg class="ml-2" width="12" height="12" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M6 10a.996.996 0 0 1-.707-.293l-5-5a1 1 0 1 1 1.414-1.414L6 7.587l4.294-4.293a1 1 0 1 1 1.414 1.414l-5 5A.997.997 0 0 1 6 10Z"
                                    fill="#E4E4E4" />
                            </svg>
                        </button>
                        <div x-ref="panel" x-show="open" x-transition.origin.top.left
                            x-on:click.outside="close($refs.button)" style="display: none;"
                            class="lg:absolute lg:w-48 w-full z-10 bg-white text-gray-600 py-2 top-auto mt-4 rounded">
                            <a href="https://darkssh.com/server/V2Ray"
                                class="block px-3 py-2 hover:bg-gray-200">V2Ray Vmess</a>
                            <a href="https://darkssh.com/server/Xray"
                                class="block px-3 py-2 hover:bg-gray-200">Xray Vless</a>
                        </div>
                    </div>
                    <div class="mx-4">
                        <a href="https://darkssh.com/server/Shadowsocks"
                            class="lg:w-auto w-full inline-block font-medium text-lg text-white">ShadowSocks</a>
                    </div>
                    <div class="mx-4 py-2 lg:py-0 relative" x-data="dropdown"
                        x-on:keydown.escape.prevent.stop="close($refs.button)"
                        x-on:focusin.window="! $refs.panel.contains($event.target) && close()">
                        <button x-on:click="toggle()" type="button" x-ref="button"
                            class="lg:w-auto w-full font-medium text-lg flex items-center text-gray-200">
                            Tools
                            <svg class="ml-2" width="12" height="12" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M6 10a.996.996 0 0 1-.707-.293l-5-5a1 1 0 1 1 1.414-1.414L6 7.587l4.294-4.293a1 1 0 1 1 1.414 1.414l-5 5A.997.997 0 0 1 6 10Z"
                                    fill="#E4E4E4" />
                            </svg>
                        </button>
                        <div x-ref="panel" x-show="open" x-transition.origin.top.left
                            x-on:click.outside="close($refs.button)" style="display: none;"
                            class="lg:absolute lg:w-40 w-full z-10 bg-white text-gray-600 py-2 top-auto mt-4 rounded">
                            <a href="https://darkssh.com/page/host-to-ip" class="block px-3 py-2 hover:bg-gray-200">Host to
                                IP</a>
                            <a href="http://ping.eu/ping/" class="block px-3 py-2 hover:bg-gray-200">Ping</a>
                            <a href="http://ping.eu/proxy/" class="block px-3 py-2 hover:bg-gray-200">Proxy Check</a>
                        </div>
                    </div>
                    <div class="mx-4 py-2 lg:py-0 relative" x-data="dropdown"
                        x-on:keydown.escape.prevent.stop="close($refs.button)"
                        x-on:focusin.window="! $refs.panel.contains($event.target) && close()">
                        <button x-on:click="toggle()" type="button" x-ref="button"
                            class="lg:w-auto w-full font-medium text-lg flex items-center text-gray-200">
                            Pages
                            <svg class="ml-2" width="12" height="12" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M6 10a.996.996 0 0 1-.707-.293l-5-5a1 1 0 1 1 1.414-1.414L6 7.587l4.294-4.293a1 1 0 1 1 1.414 1.414l-5 5A.997.997 0 0 1 6 10Z"
                                    fill="#E4E4E4" />
                            </svg>
                        </button>
                        <div x-ref="panel" x-show="open" x-transition.origin.top.left
                            x-on:click.outside="close($refs.button)" style="display: none;"
                            class="lg:absolute lg:w-40 w-full z-10 bg-white text-gray-600 py-2 top-auto mt-4 rounded">
                            
                                                            <a href="https://darkssh.com/page/about"
                                    class="block px-3 py-2 hover:bg-gray-200">About</a>
                                                            <a href="https://darkssh.com/page/contact"
                                    class="block px-3 py-2 hover:bg-gray-200">Contact Us</a>
                                                            <a href="https://darkssh.com/page/disclaimer"
                                    class="block px-3 py-2 hover:bg-gray-200">Disclaimer</a>
                                                            <a href="https://darkssh.com/page/term-of-service"
                                    class="block px-3 py-2 hover:bg-gray-200">Terms of Service</a>
                            
                                                    </div>
                    </div>
                    <div class="ml-4 mt-2 lg:mt-0 lg:mr-0 mr-4">
                        <a href="https://darkssh.com#serverType"
                            class="lg:w-auto w-full bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 inline-flex items-center justify-center shadow-sm rounded transition-colors duration-150">Create
                            Now</a>
                    </div>
                </nav>
            </div>
        </div>
    </header>

            <div class="container max-w-screen-xl mx-auto">
            <div class="grid md:grid-cols-2 py-20">
                <div class="text-gray-200">
                    <h1 class="font-bold text-5xl leading-snug mb-10 relative wow animate__fadeInLeft"
                        data-wow-duration="0.3s"
                    >
                        Put Darkness to Hide <br/> Your Identity
                        <span class="absolute w-48 h-10 bg-primary-normal -bottom-1 right-72 -z-10"></span>
                    </h1>
                    <p class="max-w-md text-lg mb-8 wow animate__fadeInLeft"
                        data-wow-delay="0.2s"
                        data-wow-duration="0.3s">
                        With strong tunneling security will help you to hide and secure your personal identity while surfing on the internet.
                    </p>
                    <a href="#serverType"
                        class="text-lg font-semibold flex items-center group relative mb-10 wow animate__fadeInLeft"
                        data-wow-delay="0.3s"
                        data-wow-duration="0.3s"
                    >
                        Discover Darkness
                        <span class="ml-2 group-hover:ml-4 transition-all duration-150"><svg width="27" height="16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M1 7a1 1 0 0 0 0 2V7Zm25.707 1.707a1 1 0 0 0 0-1.414L20.343.929a1 1 0 1 0-1.414 1.414L24.586 8l-5.657 5.657a1 1 0 0 0 1.414 1.414l6.364-6.364ZM1 9h25V7H1v2Z" fill="#E4E4E4"/></svg></span>
                        <span class="absolute border-b border-gray-200 border-2 -bottom-2 w-10"></span>
                    </a>

                    <div
                        class="flex wow animate__fadeInUp"
                        data-wow-delay="0.2s"
                        data-wow-duration="0.3s"
                    >
                                                <div class="flex flex-col mr-8">
                            <span class="text-4xl font-bold mb-2">225.6k</span>
                            <span class="text-gray-400">Users already<br/>created.</span>
                        </div>
                        <div class="flex flex-col">
                            <span class="text-4xl font-bold mb-2">45</span>
                            <span class="text-gray-400">Available<br/>servers.</span>
                        </div>
                    </div>
                </div>
                <div class="place-self-end wow animate__zoomIn md:mt-0 -mt-10 relative -z-10"
                    data-wow-delay="0.2s"
                    data-wow-duration="0.4s"
                >
                    <img src="https://darkssh.com/images/home_illustration.svg" class="max-w-full px-8" alt="home_illustration.svg" />
                </div>
            </div>
        </div>
    

    
            <div class="container max-w-screen-xl mx-auto py-13">
            <div class="text-gray-200 mb-13">
        <h2 class="text-3.5xl text-center font-bold mb-6 wow animate__fadeInUp"
            data-wow-duration="0.3s"
        >
            Specialized Tunneling Features<br/>for Our Users
        </h2>
        <p class="max-w-2xl text-center mx-auto wow animate__fadeInUp"
            data-wow-delay="0.2s"
            data-wow-duration="0.2s"
        >
            This is why we recommend our tunneling service to to our users and visitors. You can rate our services after reading this fetures and trying our services.
        </p>
    </div>
        
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div class="bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 wow animate__fadeInUp"
            data-wow-duration="0.2s"
        >
            <div class="w-18 h-18 overflow-hidden">
                <img src="https://darkssh.com/images/icon-undetectable.svg" class="w-full" alt="icon-undetectable.svg" />
            </div>
            <h3 class="font-bold text-lg my-4">Keep Undetectable</h3>
            <p>
                Don't let anyone know your life while using internet. Keep self secure and undetectable.
            </p>
        </div>
        <div class="bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 wow animate__fadeInUp"
            data-wow-delay="0.1s"
            data-wow-duration="0.2s"
        >
            <div class="w-18 h-18 overflow-hidden">
                <img src="https://darkssh.com/images/icon-stable-signal.svg" class="w-full" alt="icon-stable-signal.svg" />
            </div>
            <h3 class="font-bold text-lg my-4">Stable Server</h3>
            <p>
                Our service using strong server with 99.99% uptime. Feel more safety.
            </p>
        </div>
        <div class="bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 wow animate__fadeInUp"
            data-wow-delay="0.2s"
            data-wow-duration="0.2s"
        >
            <div class="w-18 h-18 overflow-hidden">
                <img src="https://darkssh.com/images/icon-acceleration.svg" class="w-full" alt="icon-acceleration.svg" />
            </div>
            <h3 class="font-bold text-lg my-4">Strong Acceleration</h3>
            <p>
                Our tunneling server at least have 1GBps I/O Port and unmetered bandwidth usage.
            </p>
        </div>
        <div class="bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 wow animate__fadeInUp"
            data-wow-delay="0.3s"
            data-wow-duration="0.2s"
        >
            <div class="w-18 h-18 overflow-hidden">
                <img src="https://darkssh.com/images/icon-geo-unrestricted.svg" class="w-full" alt="icon-geo-unrestricted.svg" />
            </div>
            <h3 class="font-bold text-lg my-4">Unlock Geo-Restriction</h3>
            <p>
                Browse everywhere anytime without limitation to visiting any sites around the world.
            </p>
        </div>
    </div>
    </div>        
        <div class="flex justify-center my-4">
            <script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- wahyus -->
<ins class="adsbygoogle"
     style="display:block;max-width:970px;width:100%;margin:0 auto;"
     data-ad-client="ca-pub-2683295470677090"
     data-ad-slot="2877006766"
     data-ad-format="auto"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>
        </div>

        <div class="container max-w-screen-xl my-10 mx-auto border-y border-white border-opacity-10">
    <div class="grid grid-cols-2 md:grid-cols-5 justify-center lg:gap-20 wow animate__fadeInUp"
        data-wow-duration="0.3s"
    >
        <img class="cursor-pointer opacity-40 w-full md:w-auto" title="Ubuntu" src="https://darkssh.com/images/icon-ubuntu.png" alt="ubuntu" />
        <img class="cursor-pointer opacity-40 w-full md:w-auto" title="Debian" src="https://darkssh.com/images/icon-debian.png" alt="debian" />
        <img class="cursor-pointer opacity-40 w-full md:w-auto" title="Websocket" src="https://darkssh.com/images/icon-websocket.png" alt="websocket" />
        <img class="cursor-pointer opacity-40 w-full md:w-auto" title="SSH" src="https://darkssh.com/images/icon-ssh.png" alt="ssh" />
        <img class="cursor-pointer opacity-40 w-full md:w-auto" title="OpenVPN" src="https://darkssh.com/images/icon-openvpn.png" alt="openvpn" />
    </div>
</div>
        <div class="container max-w-screen-xl my-20 mx-auto">
    <div class="grid md:grid-cols-2 gap-8 items-center">
        <div class="text-gray-200">
            <h2 class="text-3.5xl font-bold mb-5 wow animate__fadeInLeft"
                data-wow-duration="0.3s"
            >
                Connnect Everywhere Around <br/> The World
            </h2>
            <p class="text-xl wow animate__fadeInLeft"
                data-wow-delay="0.1s"
                data-wow-duration="0.3s"
            >
                You can change your connection location from around the world, because our servers available from many countries.
            </p>
        </div>
        <div  class="wow animate__zoomIn"
            data-wow-delay="0.2s"
            data-wow-duration="0.3s"
        >
            <img src="https://darkssh.com/images/illustration-world-map.png" class="max-w-full px-4" alt="illustration-world-map.png" />
        </div>
    </div>
</div>

<div class="container max-w-screen-xl my-20 mx-auto overflow-hidden">
    <div class="grid md:grid-cols-2 gap-8 items-center">
        <div class="wow animate__zoomIn"
            data-wow-delay="0.1s"
            data-wow-duration="0.3s"
        >
            <img src="https://darkssh.com/images/illustration-puzzle.png" class="max-w-full px-4" alt="illustration-world-map.png" />
        </div>
        <div class="text-gray-200">
            <h2 class="text-3.5xl font-bold mb-5 wow animate__fadeInRight"
                data-wow-duration="0.3s"
            >
                Multiple Secure Solution Make<br/>More Strong Connection
            </h2>
            <p class="text-xl wow animate__fadeInRight"
                data-wow-delay="0.1s"
                data-wow-duration="0.3s"
            >
                Strong connection make your life on internet hard to decrypt. We provides multiple tunneling service.
            </p>
        </div>
    </div>
</div>
        <div class="flex justify-center my-4">
            <script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- wahyus -->
<ins class="adsbygoogle"
     style="display:block;max-width:970px;width:100%;margin:0 auto;"
     data-ad-client="ca-pub-2683295470677090"
     data-ad-slot="2877006766"
     data-ad-format="auto"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>
        </div>

        <div class="container max-w-screen-xl py-13 mx-auto border-y border-white border-opacity-10 text-center text-gray-200">
    <h2 class="text-3.5xl font-bold mb-6 wow animate__fadeInUp" data-wow-duration="0.3s">
        Ready to Fill Darkness Into Your<br />Connection?
    </h2>
    <p class="text-lg max-w-2xl mx-auto mb-8 wow animate__fadeInUp" data-wow-delay="0.2s" data-wow-duration="0.3s">
        Fill darkness into your connection make your self more secure and undetectable while living on the internet
        world.
    </p>
    <a href="#serverType"
        class="bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 inline-flex items-center justify-center shadow-sm rounded transition-colors duration-150 wow animate__fadeInUp"
        data-wow-delay="0.3s" data-wow-duration="0.3s">
        Start Create Account
    </a>
    <div class="flex items-center md:flex-row flex-col gap-y-4 md:gap-y-0 flex-wrap justify-center mt-8">
        <div class="flex items-center font-semibold md:mr-13 wow animate__fadeInUp" data-wow-delay="0.4s"
            data-wow-duration="0.2s">
            <svg class="mr-3" width="24" height="24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M12 1C5.925 1 1 5.925 1 12s4.925 11 11 11 11-4.925 11-11S18.075 1 12 1Zm4.768 9.14a1.001 1.001 0 1 0-1.536-1.28l-4.3 5.159-2.225-2.226a1 1 0 0 0-1.414 1.414l3 3a1.002 1.002 0 0 0 1.475-.067l5-6Z"
                    fill="#5E57CA" />
            </svg>
            <span>Free Forever</span>
        </div>
        <div class="flex items-center font-semibold md:mr-13 wow animate__fadeInUp" data-wow-delay="0.5s"
            data-wow-duration="0.2s">
            <svg class="mr-3" width="24" height="24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M12 1C5.925 1 1 5.925 1 12s4.925 11 11 11 11-4.925 11-11S18.075 1 12 1Zm4.768 9.14a1.001 1.001 0 1 0-1.536-1.28l-4.3 5.159-2.225-2.226a1 1 0 0 0-1.414 1.414l3 3a1.002 1.002 0 0 0 1.475-.067l5-6Z"
                    fill="#5E57CA" />
            </svg>
            <span>Multiple Tunneling Types</span>
        </div>
        <div class="flex items-center font-semibold wow animate__fadeInUp" data-wow-delay="0.6s"
            data-wow-duration="0.2s">
            <svg class="mr-3" width="24" height="24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M12 1C5.925 1 1 5.925 1 12s4.925 11 11 11 11-4.925 11-11S18.075 1 12 1Zm4.768 9.14a1.001 1.001 0 1 0-1.536-1.28l-4.3 5.159-2.225-2.226a1 1 0 0 0-1.414 1.414l3 3a1.002 1.002 0 0 0 1.475-.067l5-6Z"
                    fill="#5E57CA" />
            </svg>
            <span>No Logging Activity</span>
        </div>
    </div>
</div>

<div class="container max-w-screen-xl mx-auto py-13" id="serverType">
            <div class="flex flex-wrap justify-center gap-8">
        <div class="lg:w-3/12 md:w-6/12 w-full bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 flex flex-col items-center wow animate__fadeIn"
            data-wow-duration="0.2s">
            <h3 class="font-bold text-1xl xl:text-2xl">SSH Server</h3>
            <img src="https://darkssh.com/images/icon-ssh.png" alt="icon-ssh.png" />
            <p class="mb-8">
                11 Servers available
            </p>
            <a href="https://darkssh.com/server/SSH"
                class="bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 flex w-full items-center justify-center shadow-sm rounded transition-colors duration-150">Create
                Account</a>
        </div>
        <div class="lg:w-3/12 md:w-6/12 w-full bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 flex flex-col items-center wow animate__fadeIn"
            data-wow-duration="0.2s">
            <h3 class="font-bold text-1xl xl:text-2xl">SSH UDP</h3>
            <img src="https://darkssh.com/images/icon-ssh.png" alt="icon-ssh.png" />
            <p class="mb-8">
                8 Servers available
            </p>
            <a href="https://darkssh.com/server/UDP"
                class="bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 flex w-full items-center justify-center shadow-sm rounded transition-colors duration-150">Create
                Account</a>
        </div>
        <div class="lg:w-3/12 md:w-6/12 w-full bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 flex flex-col items-center wow animate__fadeIn"
            data-wow-duration="0.2s">
            <h3 class="font-bold text-1xl xl:text-2xl">SSH SlowDNS</h3>
            <img src="https://darkssh.com/images/icon-ssh.png" alt="icon-ssh.png" />
            <p class="mb-8">
                9 Servers available
            </p>
            <a href="https://darkssh.com/server/Slowdns"
                class="bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 flex w-full items-center justify-center shadow-sm rounded transition-colors duration-150">Create
                Account</a>
        </div>
        <div class="lg:w-3/12 md:w-6/12 w-full bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 flex flex-col items-center wow animate__fadeIn"
            data-wow-duration="0.2s">
            <h3 class="font-bold text-1xl xl:text-2xl">OpenVPN </h3>
            <img src="https://darkssh.com/images/icon-openvpn.png" alt="icon-openvpn.png" />
            <p class="mb-8">
                6 Servers available
            </p>
            <a href="https://darkssh.com/server/OpenVPN"
                class="bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 flex w-full items-center justify-center shadow-sm rounded transition-colors duration-150">Create
                Account</a>
        </div>
        <div class="lg:w-3/12 md:w-6/12 w-full bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 flex flex-col items-center wow animate__fadeIn"
            data-wow-duration="0.2s">
            <h3 class="font-bold text-1xl xl:text-2xl">V2Ray Vmess </h3>
            <img src="https://darkssh.com/images/icon-websocket.png" alt="icon-websocket.png" />
            <p class="mb-8">
                4 Servers available
            </p>
            <a href="https://darkssh.com/server/V2Ray"
                class="bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 flex w-full items-center justify-center shadow-sm rounded transition-colors duration-150">Create
                Account</a>
        </div>
        <div class="lg:w-3/12 md:w-6/12 w-full bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 flex flex-col items-center wow animate__fadeIn"
            data-wow-duration="0.2s">
            <h3 class="font-bold text-1xl xl:text-2xl">Xray Vless </h3>
            <img src="https://darkssh.com/images/icon-websocket.png" alt="icon-websocket.png" />
            <p class="mb-8">
                0 Servers available
            </p>
            <a href="https://darkssh.com/server/Xray"
                class="bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 flex w-full items-center justify-center shadow-sm rounded transition-colors duration-150">Create
                Account</a>
        </div>

        <div class="lg:w-3/12 md:w-6/12 w-full bg-primary-normal bg-opacity-12 p-8 rounded-xl text-gray-200 flex flex-col items-center wow animate__fadeIn"
            data-wow-duration="0.2s">
            <h3 class="font-bold text-1xl xl:text-2xl">ShadowSocks</h3>
            <img src="https://darkssh.com/images/icon-debian.png" alt="icon-websocket.png" />
            <p class="mb-8">
                7 Servers available
            </p>
            <a href="https://darkssh.com/server/Shadowsocks"
                class="bg-primary-normal hover:bg-primary-dark font-semibold text-white h-13 py-2 px-4 flex w-full items-center justify-center shadow-sm rounded transition-colors duration-150">Create
                Account</a>
        </div>

    </div>
    </div>

        <div class="flex justify-center my-4">
            <script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- wahyus -->
<ins class="adsbygoogle"
     style="display:block;max-width:970px;width:100%;margin:0 auto;"
     data-ad-client="ca-pub-2683295470677090"
     data-ad-slot="2877006766"
     data-ad-format="auto"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>
        </div>
    
<footer class="bg-footer pt-56 -mx-6 px-6">
    <div class="container max-w-screen-xl mx-auto">
        <div class="flex items-center md:flex-row flex-col gap-8 justify-between md:text-left">
            <a href="https://darkssh.com" class="self-center">
                                <img src="https://darkssh.com/images/1648565419_logo.svg" alt="Logo">
                            </a>
            <nav class="flex items-center gap-3">
                                <a href="https://fb.me/duwiwahyu" target="_blank" rel="noopener"><svg class="fill-gray-200 hover:fill-white" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="24" height="24" style="vertical-align: -0.143em;-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 896 1792"><path d="M895 12v264H738q-86 0-116 36t-30 108v189h293l-39 296H592v759H286V905H31V609h255V391q0-186 104-288.5T667 0q147 0 228 12z"/></svg></a>
                <a href="https://twitter.com/duwiwahyu" target="_blank" rel="noopener"><svg class="fill-gray-200 hover:fill-white" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="24" height="24" style="vertical-align: -0.143em;-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 -256 1600 1792"><path d="M1588 152q-67 98-162 167q1 14 1 42q0 130-38 259.5T1273.5 869T1089 1079.5t-258 146t-323 54.5q-271 0-496-145q35 4 78 4q225 0 401-138q-105-2-188-64.5T189 777q33 5 61 5q43 0 85-11q-112-23-185.5-111.5T76 454v-4q68 38 146 41q-66-44-105-115T78 222q0-88 44-163q121 149 294.5 238.5T788 397q-8-38-8-74q0-134 94.5-228.5T1103 0q140 0 236 102q109-21 205-78q-37 115-142 178q93-10 186-50z"/></svg></a>
                <a href="https://instagram.com/duwiwahyu" target="_blank" rel="noopener"><svg class="fill-gray-200 hover:fill-white" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="24" height="24" style="vertical-align: -0.143em;-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 -128 1536 1792"><path d="M1024 768q0-106-75-181t-181-75t-181 75t-75 181t75 181t181 75t181-75t75-181zm138 0q0 164-115 279t-279 115t-279-115t-115-279t115-279t279-115t279 115t115 279zm108-410q0 38-27 65t-65 27t-65-27t-27-65t27-65t65-27t65 27t27 65zM768 138q-7 0-76.5-.5t-105.5 0t-96.5 3t-103 10T315 169q-50 20-88 58t-58 88q-11 29-18.5 71.5t-10 103t-3 96.5t0 105.5t.5 76.5t-.5 76.5t0 105.5t3 96.5t10 103T169 1221q20 50 58 88t88 58q29 11 71.5 18.5t103 10t96.5 3t105.5 0t76.5-.5t76.5.5t105.5 0t96.5-3t103-10t71.5-18.5q50-20 88-58t58-88q11-29 18.5-71.5t10-103t3-96.5t0-105.5t-.5-76.5t.5-76.5t0-105.5t-3-96.5t-10-103T1367 315q-20-50-58-88t-88-58q-29-11-71.5-18.5t-103-10t-96.5-3t-105.5 0t-76.5.5zm768 630q0 229-5 317q-10 208-124 322t-322 124q-88 5-317 5t-317-5q-208-10-322-124T5 1085q-5-88-5-317t5-317q10-208 124-322T451 5q88-5 317-5t317 5q208 10 322 124t124 322q5 88 5 317z"/></svg></a>
                <a href="https://t.me/duwiwahyu" target="_blank" rel="noopener"><svg class="fill-gray-200 hover:fill-white" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="24" height="24" style="vertical-align: -0.143em;-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 1792 1792"><path d="M1189 1307l147-693q9-44-10.5-63t-51.5-7L410 877q-29 11-39.5 25t-2.5 26.5t32 19.5l221 69l513-323q21-14 32-6q7 5-4 15l-415 375l-16 228q23 0 45-22l108-104l224 165q64 36 81-38zm603-411q0 182-71 348t-191 286t-286 191t-348 71t-348-71t-286-191t-191-286T0 896t71-348t191-286T548 71T896 0t348 71t286 191t191 286t71 348z"/></svg></a>
            </nav>
        </div>
                <div class="text-center md:text-left py-8 mt-8 border-t border-white border-opacity-10 text-gray-200 flex md:flex-row flex-col items-center justify-between">
            <p>&copy; Copyright 2024. <strong><a href="https://darkssh.com">DarkSSH</a></strong></p>
            <nav class="flex gap-4 flex-wrap justify-center mt-4 md:mt-0 md:justify-end">
                                    <a href="https://darkssh.com/page/about">About</a>
                                    <a href="https://darkssh.com/page/contact">Contact Us</a>
                                    <a href="https://darkssh.com/page/disclaimer">Disclaimer</a>
                                    <a href="https://darkssh.com/page/term-of-service">Terms of Service</a>
                            </nav>
        </div>
    </div>
</footer>

<script id="__bs_script__">//<![CDATA[
    document.write("<script async src='http://HOST:3000/browser-sync/browser-sync-client.js'><\/script>".replace("HOST", location.hostname));
//]]></script>
</body>
</html>
