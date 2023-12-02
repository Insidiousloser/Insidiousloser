<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
        <meta name="facebook-domain-verification" content="rqsdwhkm3cd7bdia50dim89maue974" />
        <title>Zombs Royale - 100 Player 2D Real-Time Battle Royale</title>
                        <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Open+Sans:400,600">

                            <link rel="stylesheet" href="/asset/app.css?077fff8" type="text/css">
                    

    <meta name="google-site-verification" content="BAf_ZX4_O4bItOkIOGEceQ9LAAOzJTn7s3UOInVzveI">
    <meta name="google-site-verification" content="gCky0JI_PK5WTalCiPJBrgdCPOfWM76oLZ_TY4Ci5FA">

            <meta name="description" content="Play ZombsRoyale.io - 100 player 2D real-time massive multiplayer Battle Royale game in your browser, inspired by PUBG/Fortnite.">
        <meta name="twitter:card" content="summary">
        <meta name="twitter:site" content="@zombsroyale">
        <meta name="og:title" content="ZombsRoyale.io">
        <meta name="og:description" content="Play ZombsRoyale.io - 100 player 2D real-time massive multiplayer Battle Royale game in your browser, inspired by PUBG/Fortnite.">
        <meta name="og:image" content="http://zombsroyale.io/asset/image/share-card.png">
                        <script src="https://lngtd.com/zombsroyale.js"></script>
            </head>

    <body class="home">
            <div class="home-loading">
        <div class="home-loading-props">
            <div class="home-loading-tree"></div>
            <div class="home-loading-tree"></div>
            <div class="home-loading-tree"></div>
            <div class="home-loading-player-scar"></div>
            <div class="home-loading-player-regular"></div>
        </div>
        <div class="home-loading-logo"></div>
        <div class="home-loading-tiers">
            <span class="tier-common"></span>
            <span class="tier-uncommon"></span>
            <span class="tier-rare"></span>
            <span class="tier-epic"></span>
            <span class="tier-legendary"></span>
            <span class="tier-mythic"></span>
        </div>
        <div class="home-loading-tip">Tip: Pick up higher quality weapons if you can, they pack more of a punch! - &copy; Lol Analytics, LLC 2023</div>
        <div class="home-loading-help">
            <div class="help-box">
                <span class="help-box-images">
                    <span class="help-box-image help-box-image-left" style="background-image:url('/asset/image/help-one-left.png');"></span>
                    <span class="help-box-image help-box-image-right" style="background-image:url('/asset/image/help-one-right.png');"></span>
                </span>
                <span class="help-box-label">
                    <p><strong>WASD</strong> or <strong>Arrow Keys</strong> to move</p>
                    <p><strong>Left Mouse</strong> to fire</p>
                </span>
            </div>
            <div class="help-box">
                <span class="help-box-images">
                    <span class="help-box-image help-box-image-left" style="background-image:url('/asset/image/help-two-left.png');"></span>
                    <span class="help-box-image help-box-image-right" style="background-image:url('/asset/image/help-two-right.png');"></span>
                </span>
                <span class="help-box-label">
                    <p>Break shiny boxes to get loot</p>
                </span>
            </div>
            <div class="help-box">
                <span class="help-box-images">
                    <span class="help-box-image help-box-image-left" style="background-image:url('/asset/image/help-three-left.png');"></span>
                    <span class="help-box-image help-box-image-right" style="background-image:url('/asset/image/help-three-right.png');"></span>
                </span>
                <span class="help-box-label">
                    <p>Press <strong>E</strong> to open doors</p>
                </span>
            </div>
            <div class="help-box">
                <span class="help-box-images">
                    <span class="help-box-image help-box-image-left" style="background-image:url('/asset/image/help-four-left.png');"></span>
                    <span class="help-box-image help-box-image-right" style="background-image:url('/asset/image/help-four-right.png');"></span>
                </span>
                <span class="help-box-label">
                    <p>Press <strong>E</strong> to interact and loot chests</p>
                </span>
            </div>
        </div>
    </div>
            <script src="/asset/app.js?16c91aa"></script>
        <script src="/asset/build/webgl.loader.js?22409c8"></script>
    <script>
        Sentry.init({
            dsn: 'https://352cbbac574d4cb3b1ee60be131cd19b@sentry.end.gg/2',
            environment: 'prod',
            release: '8a3173f1570d2b512c74a5a1b677959518d6c95a',
            maxBreadcrumbs: 0,
            instrument: false,
            whitelistUrls: [
                'http://zombsroyale.io',
                'https://zombsroyale.io'
            ],
            beforeSend: function(e, hint) {
                var rewriteErrors = {
                    'Cannot enlarge memory arrays': 'Exhausted available memory limit while running game...',
                    'out of memory': 'Exhausted available memory limit while running game...'
                };

                for (var originalMatch in rewriteErrors) {
                    if (e.message && e.message.indexOf(originalMatch) > -1) {
                        e.message = rewriteErrors[originalMatch];
                        break;
                    }
                }

                Sentry.trackedErrors = 'trackedErrors' in Sentry ? Sentry.trackedErrors + 1 : 1;

                if (Sentry.trackedErrors > 10) {
                    return null;
                }

                return e;
            }
        });

        var game = new Game({
            stage: 'prod',
            endpoint: 'zombsroyale',
            userData: false,
            dataUrl: '/asset/build/webgl.data.br?9a909ed',
            frameworkUrl: '/asset/build/webgl.framework.js.br?b895c74',
            codeUrl: '/asset/build/webgl.wasm.br?97c8a15',
            streamingAssetsUrl: '/asset/build/StreamingAssets',
                    });

        game.init();
    </script>
    <script src="//static.xsolla.com/embed/paystation/1.0.7/widget.min.js" async></script>
                    <script async src="https://www.googletagmanager.com/gtag/js?id=G-LK8Q86PZ5G"></script>
            <script>
                window.dataLayer = window.dataLayer || [];
                function gtag() { dataLayer.push(arguments); }
                gtag('js', new Date());
                gtag('config', 'G-LK8Q86PZ5G');
                gtag('config', 'UA-115440498-1'); // Older tag
            </script>
            <script>
                !function(f,b,e,v,n,t,s)
                {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
                n.callMethod.apply(n,arguments):n.queue.push(arguments)};
                if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
                n.queue=[];t=b.createElement(e);t.async=!0;
                t.src=v;s=b.getElementsByTagName(e)[0];
                s.parentNode.insertBefore(t,s)}(window, document,'script',
                'https://connect.facebook.net/en_US/fbevents.js');

                fbq('init', '231520644073398');
                fbq('track', 'PageView');
            </script>
            <noscript>
                <img height="1" width="1" style="display:none" src="https://www.facebook.com/tr?id=231520644073398&ev=PageView&noscript=1">
            </noscript>
                <div id="cdm-zone-end"></div>
    </body>
</html>
