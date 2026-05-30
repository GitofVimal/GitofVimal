# GitofVimal

<svg xmlns="http://www.w3.org/2000/svg"
     viewBox="0 0 1441 302"
     width="1441"
     height="302"
     style="background:#ffffff">

    <defs>
        <!-- Glow -->
        <filter id="glow">
            <feGaussianBlur stdDeviation="4" result="blur"/>
            <feMerge>
                <feMergeNode in="blur"/>
                <feMergeNode in="SourceGraphic"/>
            </feMerge>
        </filter>

        <!-- Stronger glow for meteors -->
        <filter id="meteorGlow">
            <feGaussianBlur stdDeviation="3" result="blur"/>
            <feMerge>
                <feMergeNode in="blur"/>
                <feMergeNode in="blur"/>
                <feMergeNode in="SourceGraphic"/>
            </feMerge>
        </filter>

        <!-- Gradient for waves -->
        <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#f59e0b"/>
            <stop offset="50%" stop-color="#fbbf24"/>
            <stop offset="100%" stop-color="#f59e0b"/>
        </linearGradient>

        <!-- Gradient for glowing circle -->
        <linearGradient id="glowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#f59e0b"/>
            <stop offset="50%" stop-color="#f59e0b"/>
            <stop offset="100%" stop-color="#f59e0b"/>
        </linearGradient>

        <!-- Meteor trail gradients -->
        
        <linearGradient id="trail-1780135495176" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#3776AB" stop-opacity="0"/>
            <stop offset="100%" stop-color="#3776AB" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1780135502657" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#00618a" stop-opacity="0"/>
            <stop offset="100%" stop-color="#00618a" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1780135523759" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#4dabcf" stop-opacity="0"/>
            <stop offset="100%" stop-color="#4dabcf" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1780135537008" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#888888" stop-opacity="0"/>
            <stop offset="100%" stop-color="#888888" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1780135550646" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#433b6b" stop-opacity="0"/>
            <stop offset="100%" stop-color="#433b6b" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1780135616162" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#e6ad10" stop-opacity="0"/>
            <stop offset="100%" stop-color="#e6ad10" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1780135636495" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#34a853" stop-opacity="0"/>
            <stop offset="100%" stop-color="#34a853" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1780135688099" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#888888" stop-opacity="0"/>
            <stop offset="100%" stop-color="#888888" stop-opacity="1"/>
        </linearGradient>

        <linearGradient id="trail-1780135719234" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" stop-color="#040506" stop-opacity="0"/>
            <stop offset="100%" stop-color="#040506" stop-opacity="1"/>
        </linearGradient>

        <!-- Circle clip for avatar -->
        <clipPath id="avatarClip">
            <circle cx="720.5" cy="151" r="75"/>
        </clipPath>
    </defs>

    <!-- Background waves -->
    <path d="M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151"
          fill="none"
          stroke="url(#waveGrad)"
          stroke-width="2"
          opacity="0.5">
        <animate attributeName="d"
                 dur="6s"
                 repeatCount="indefinite"
                 values="
             M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151;
             M0 151 Q180 181 360 151 T721 151 T1081 151 T1441 151;
             M0 151 Q180 121 360 151 T721 151 T1081 151 T1441 151"/>
    </path>

    <!-- ========== METEOR LOGOS ========== -->
    
            <!-- logos:python Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="723.4000640886844" y1="-50" x2="736.3410163438105" y2="-1.7037086855465873" stroke="url(#trail-1780135495176)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="723.4000640886844;840.3862724750238" dur="10s" repeatCount="indefinite" begin="6s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="6s"/>
                    <animate attributeName="x2" values="736.3410163438105;853.3272247301499" dur="10s" repeatCount="indefinite" begin="6s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="6s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxLjAxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjU2IDI1NSI+PGRlZnM+PGxpbmVhckdyYWRpZW50IGlkPSJTVkdnMzlXbGVlUCIgeDE9IjEyLjk1OSUiIHgyPSI3OS42MzklIiB5MT0iMTIuMDM5JSIgeTI9Ijc4LjIwMSUiPjxzdG9wIG9mZnNldD0iMCUiIHN0b3AtY29sb3I9IiMzODdlYjgiLz48c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMzNjY5OTQiLz48L2xpbmVhckdyYWRpZW50PjxsaW5lYXJHcmFkaWVudCBpZD0iU1ZHbFhvUmtjNFQiIHgxPSIxOS4xMjglIiB4Mj0iOTAuNzQyJSIgeTE9IjIwLjU3OSUiIHkyPSI4OC40MjklIj48c3RvcCBvZmZzZXQ9IjAlIiBzdG9wLWNvbG9yPSIjZmZlMDUyIi8+PHN0b3Agb2Zmc2V0PSIxMDAlIiBzdG9wLWNvbG9yPSIjZmZjMzMxIi8+PC9saW5lYXJHcmFkaWVudD48L2RlZnM+PHBhdGggZmlsbD0idXJsKCNTVkdnMzlXbGVlUCkiIGQ9Ik0xMjYuOTE2LjA3MmMtNjQuODMyIDAtNjAuNzg0IDI4LjExNS02MC43ODQgMjguMTE1bC4wNzIgMjkuMTI4aDYxLjg2OHY4Ljc0NUg0MS42MzFTLjE0NSA2MS4zNTUuMTQ1IDEyNi43N2MwIDY1LjQxNyAzNi4yMSA2My4wOTcgMzYuMjEgNjMuMDk3aDIxLjYxdi0zMC4zNTZzLTEuMTY1LTM2LjIxIDM1LjYzMi0zNi4yMWg2MS4zNjJzMzQuNDc1LjU1NyAzNC40NzUtMzMuMzE5VjMzLjk3UzE5NC42Ny4wNzIgMTI2LjkxNi4wNzJNOTIuODAyIDE5LjY2YTExLjEyIDExLjEyIDAgMCAxIDExLjEzIDExLjEzYTExLjEyIDExLjEyIDAgMCAxLTExLjEzIDExLjEzYTExLjEyIDExLjEyIDAgMCAxLTExLjEzLTExLjEzYTExLjEyIDExLjEyIDAgMCAxIDExLjEzLTExLjEzIi8+PHBhdGggZmlsbD0idXJsKCNTVkdsWG9Sa2M0VCkiIGQ9Ik0xMjguNzU3IDI1NC4xMjZjNjQuODMyIDAgNjAuNzg0LTI4LjExNSA2MC43ODQtMjguMTE1bC0uMDcyLTI5LjEyN0gxMjcuNnYtOC43NDVoODYuNDQxczQxLjQ4NiA0LjcwNSA0MS40ODYtNjAuNzEyYzAtNjUuNDE2LTM2LjIxLTYzLjA5Ni0zNi4yMS02My4wOTZoLTIxLjYxdjMwLjM1NXMxLjE2NSAzNi4yMS0zNS42MzIgMzYuMjFoLTYxLjM2MnMtMzQuNDc1LS41NTctMzQuNDc1IDMzLjMydjU2LjAxM3MtNS4yMzUgMzMuODk3IDYyLjUxOCAzMy44OTdtMzQuMTE0LTE5LjU4NmExMS4xMiAxMS4xMiAwIDAgMS0xMS4xMy0xMS4xM2ExMS4xMiAxMS4xMiAwIDAgMSAxMS4xMy0xMS4xMzFhMTEuMTIgMTEuMTIgMCAwIDEgMTEuMTMgMTEuMTNhMTEuMTIgMTEuMTIgMCAwIDEtMTEuMTMgMTEuMTMiLz48L3N2Zz4=" width="32" height="32" x="720.3410163438105" y="-17.703708685546587" >
                    <animate attributeName="x" values="720.3410163438105;837.3272247301499" dur="10s" repeatCount="indefinite" begin="6s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="6s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="6s"/>
            </g>

            <!-- devicon:mysql Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="888.418513825199" y1="-50" x2="901.3594660803251" y2="-1.7037086855465873" stroke="url(#trail-1780135502657)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="888.418513825199;1005.4047222115385" dur="10s" repeatCount="indefinite" begin="0.2s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="0.2s"/>
                    <animate attributeName="x2" values="901.3594660803251;1018.3456744666645" dur="10s" repeatCount="indefinite" begin="0.2s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="0.2s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMTI4IDEyOCI+PHBhdGggZmlsbD0iIzAwNjE4YSIgZD0iTTExNy42ODggOTguMjQyYy02Ljk3My0uMTkxLTEyLjI5Ny40NjEtMTYuODUyIDIuMzc5Yy0xLjI5My41NDctMy4zNTUuNTU5LTMuNTY2IDIuMThjLjcxMS43NDYuODIgMS44NTkgMS4zODcgMi43NzdjMS4wODYgMS43NTQgMi45MjIgNC4xMTMgNC41NTkgNS4zNTJjMS43ODkgMS4zNDggMy42MzMgMi43OTMgNS41NTEgMy45NjFjMy40MTQgMi4wODIgNy4yMjMgMy4yNyAxMC41MDQgNS4zNTJjMS45MzggMS4yMyAzLjg1OSAyLjc3NyA1Ljc1IDQuMTY0Yy45MzQuNjg0IDEuNTYzIDEuNzUgMi43NzMgMi4xOHYtLjE5NWMtLjYzNy0uODEyLS44MDEtMS45My0xLjM4Ny0yLjc3N2wtMi41NzgtMi41NzhjLTIuNTItMy4zNDQtNS43MTktNi4yODEtOS4xMTctOC43MTljLTIuNzExLTEuOTQ5LTguNzgxLTQuNTc4LTkuOTEtNy43M2wtLjE5OS0uMTk5YzEuOTIyLS4yMTkgNC4xNzItLjkxNCA1Ljk0OS0xLjM5MWMyLjk4LS43OTcgNS42NDUtLjU5IDguNzE5LTEuMzg3bDQuMTY0LTEuMTg3di0uNzkzYy0xLjU1NS0xLjU5NC0yLjY2NC0zLjcwNy00LjM1OS01LjE1MmMtNC40NDEtMy43ODEtOS4yODUtNy41NTUtMTQuMjczLTEwLjcwM2MtMi43NjYtMS43NDYtNi4xODQtMi44ODMtOS4xMTctNC4zNjNjLS45ODgtLjQ5Ni0yLjcxOS0uNzU4LTMuMzcxLTEuNTg2Yy0xLjUzOS0xLjk2MS0yLjM3OS00LjQ0OS0zLjU2Ni02LjczOGMtMi40ODgtNC43OTMtNC45My0xMC4wMjMtNy4xMzctMTUuMDY2Yy0xLjUwNC0zLjQzNy0yLjQ4NC02LjgyOC00LjM1OS05LjkxYy05LTE0Ljc5Ny0xOC42ODctMjMuNzMtMzMuNjk1LTMyLjUwOGMtMy4xOTUtMS44NjctNy4wMzktMi42MDUtMTEuMTAyLTMuNTdsLTYuNTQzLS4zOTVjLTEuMzMyLS41NTUtMi43MTUtMi4xODQtMy45NjUtMi45NzdDMTYuOTc3IDMuNTIgNC4yMjMtMy4zMTIuNTM5IDUuNjcyQy0xLjc4NSAxMS4zNCA0LjAxNiAxNi44NzEgNi4wOSAxOS43NDZjMS40NTcgMi4wMTIgMy4zMiA0LjI3MyA0LjM1OSA2LjUzOWMuNjg4IDEuNDkyLjgwNSAyLjk4NCAxLjM5MSA0LjU1OWMxLjQzOCAzLjg4MyAyLjY5NSA4LjEwOSA0LjU1OSAxMS42OTVjLjk0MSAxLjgxNiAxLjk4IDMuNzI3IDMuMTcyIDUuMzUyYy43MjcuOTk2IDEuOTggMS40MzggMi4xOCAyLjk3M2MtMS4yMjcgMS43MTUtMS4yOTcgNC4zNzUtMS45ODQgNi41NDNjLTMuMDk4IDkuNzctMS45MjYgMjEuOTEgMi41NzggMjkuMTM3YzEuMzgzIDIuMjIzIDQuNjQxIDYuOTggOS4xMTcgNS4xNTZjMy45MTgtMS41OTggMy4wNDMtNi41MzkgNC4xNjQtMTAuOTAyYy4yNTQtLjk4OC4wOTgtMS43MTUuNTk0LTIuMzc5di4xOTlsMy41NyA3LjEzM2MyLjY0MSA0LjI1NCA3LjMyNCA4LjY5OSAxMS4yOTcgMTEuNjk5YzIuMDU5IDEuNTU1IDMuNjggNC4yNDIgNi4zNDQgNS4xNTJ2LS4xOTloLS4xOTljLS41MTYtLjgwNS0xLjMyNC0xLjEzNy0xLjk4LTEuNzgxYy0xLjU1MS0xLjUyMy0zLjI3Ny0zLjQxNC00LjU1OS01LjE1NmMtMy42MTMtNC45MDItNi44MDUtMTAuMjctOS43MTEtMTUuODU1Yy0xLjM5MS0yLjY2OC0yLjU5OC01LjYwOS0zLjc3LTguMzI0Yy0uNDUzLTEuMDQ3LS40NDUtMi42MzMtMS4zODctMy4xNzJjLTEuMjgxIDEuOTg4LTMuMTcyIDMuNTk4LTQuMTY0IDUuOTQ1Yy0xLjU4MiAzLjc1NC0xLjc4OSA4LjMzNi0yLjM3NSAxMy4wODJjLS4zNDguMTI1LS4xOTUuMDM5LS4zOTguMTk5Yy0yLjc2Mi0uNjY4LTMuNzMtMy41MDgtNC43NTgtNS45NDljLTIuNTk0LTYuMTY0LTMuMDc4LTE2LjA5LS43OTMtMjMuMTkxYy41OS0xLjgzNiAzLjI2Mi03LjYxNyAyLjE4LTkuMzE2Yy0uNTE2LTEuNjkxLTIuMjE5LTIuNjcyLTMuMTcyLTMuOTY1Yy0xLjE4LTEuNTk4LTIuMzU1LTMuNzAzLTMuMTcyLTUuNTUxYy0yLjEyNS00LjgwNS0zLjExMy0xMC4yMDMtNS4zNTItMTUuMDYyYy0xLjA3LTIuMzI0LTIuODc1LTQuNjc2LTQuMzU5LTYuNzM4Yy0xLjY0NS0yLjI4OS0zLjQ4NC0zLjk3Ny00Ljc1OC02Ljc0MmMtLjQ1My0uOTg0LTEuMDY2LTIuNTU5LS4zOTgtMy41NjZjLjIxNS0uNjg0LjUxNi0uOTY5IDEuMTkxLTEuMTkxYzEuMTQ4LS44ODcgNC4zNTIuMjk3IDUuNTQ3Ljc5M2MzLjE4IDEuMzIgNS44MzIgMi41NzggOC41MjcgNC4zNjNjMS4yODkuODU1IDIuNTk4IDIuNTEyIDQuMTYgMi45NzNoMS43ODVjMi43ODkuNjQxIDUuOTE0LjE5NSA4LjUyMy45ODhjNC42MDkgMS40MDIgOC43MzggMy41ODIgMTIuNDg4IDUuOTQ5YzExLjQyMiA3LjIxNSAyMC43NjYgMTcuNDggMjcuMTU2IDI5LjczNGMxLjAyNyAxLjk3MyAxLjQ3MyAzLjg1MiAyLjM3OSA1Ljk0NWMxLjgyNCA0LjIxOSA0LjEyNSA4LjU1OSA1Ljk0MSAxMi42ODhjMS44MTYgNC4xMTMgMy41ODIgOC4yNyA2LjE0OCAxMS42OTVjMS4zNDggMS44MDEgNi41NTEgMi43NjYgOC45MTggMy43NjZjMS42Ni42OTkgNC4zNzkgMS40MyA1Ljk0OSAyLjM3OWMzIDEuODA5IDUuOTA2IDMuOTY1IDguNzIzIDUuOTQ1YzEuNDAyLjk5MiA1LjczIDMuMTY4IDUuOTQ1IDQuOTU3em0tODguNjA1LTc1LjUyYy0xLjQ1My0uMDI3LTIuNDguMTU2LTMuNTY2LjM5NXYuMTk5aC4xOTVjLjY5NSAxLjQyMiAxLjkxOCAyLjM0IDIuNzc3IDMuNTY2bDEuOTggNC4xNjRsLjE5OS0uMTk1YzEuMjI3LS44NjcgMS43ODktMi4yNSAxLjc4MS00LjM2M2MtLjQ5Mi0uNTItLjU2Mi0xLjE2NC0uOTkyLTEuNzg1Yy0uNTYyLS44MjQtMS42Ni0xLjI4OS0yLjM3NS0xLjk4em0wIDAiLz48L3N2Zz4=" width="32" height="32" x="885.3594660803251" y="-17.703708685546587" >
                    <animate attributeName="x" values="885.3594660803251;1002.3456744666645" dur="10s" repeatCount="indefinite" begin="0.2s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="0.2s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="0.2s"/>
            </g>

            <!-- devicon:numpy Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="1061.379334567112" y1="-50" x2="1074.3202868222381" y2="-1.7037086855465873" stroke="url(#trail-1780135523759)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="1061.379334567112;1178.3655429534513" dur="10s" repeatCount="indefinite" begin="4s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="4s"/>
                    <animate attributeName="x2" values="1074.3202868222381;1191.3064952085774" dur="10s" repeatCount="indefinite" begin="4s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="4s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMTI4IDEyOCI+PHBhdGggZmlsbD0iIzRkYWJjZiIgZD0ibTU1LjAxMiAyNi4wMDZsLTIxLjM4LTEwLjc4OUwxMC4xNTQgMjYuOTNsMjEuOTY5IDExLjAyN1ptOS44MDggNC45NTFMODcuMjQxIDQyLjI4TDYzLjk4MiA1My45NTVsLTIyLTExLjA0M1ptMjkuOTQ4LTE1LjU4MWwyMy4wMzcgMTEuNTUyTDk3LjIgMzcuMjcyTDc0LjczNSAyNS45MzhaTTg0Ljg1MyAxMC40TDY0LjExMyAwTDQzLjU5OCAxMC4yNEw2NC45NyAyMS4wMTRaTTY4LjY0IDk5LjcwMlYxMjhsMjUuMTIyLTEyLjUzN2wtLjAyMy0yOC4zMVpNOTMuNzI3IDc3LjI3bC0uMDI4LTI4LjAxMmwtMjUuMDYgMTIuNDU4Vjg5Ljc0Wm0zMC4xNTgtNS4yNDZ2MjguNDFsLTIxLjQzIDEwLjY5bC0uMDE3LTI4LjI3OXptMC05LjkzNVYzNC4yNWwtMjEuNDcgMTAuNjczbC4wMTYgMjguMDY4eiIvPjxwYXRoIGZpbGw9IiM0Yzc1Y2YiIGQ9Im01OS43NyA2MS43MTZsLTE2LjkxOC04LjUxMlY4OS45N3MtMjAuNy00NC4wMzMtMjIuNjEyLTQ3Ljk5Yy0uMjQ2LS41MTMtMS4yNjMtMS4wNy0xLjUyMi0xLjIwOWMtMy43MzEtMS45NDctMTQuNjAzLTcuNDUtMTQuNjAzLTcuNDV2NjQuOTc3bDE1LjA0IDguMDYzVjcyLjM4MnMyMC40NzggMzkuMzQ2IDIwLjY4OSAzOS43OGMuMjE0LjQyOSAyLjI1NyA0LjU3IDQuNDU5IDYuMDI4YzIuOTIgMS45MzkgMTUuNDU4IDkuNDc3IDE1LjQ1OCA5LjQ3N3oiLz48L3N2Zz4=" width="32" height="32" x="1058.3202868222381" y="-17.703708685546587" >
                    <animate attributeName="x" values="1058.3202868222381;1175.3064952085774" dur="10s" repeatCount="indefinite" begin="4s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="4s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="4s"/>
            </g>

            <!-- solar:figma-linear Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="354.4813474579852" y1="-50" x2="367.4222997131112" y2="-1.7037086855465873" stroke="url(#trail-1780135537008)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="354.4813474579852;471.4675558443246" dur="10s" repeatCount="indefinite" begin="1.8s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="1.8s"/>
                    <animate attributeName="x2" values="367.4222997131112;484.4085080994506" dur="10s" repeatCount="indefinite" begin="1.8s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="1.8s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxnIGZpbGw9Im5vbmUiIHN0cm9rZT0iY3VycmVudENvbG9yIiBzdHJva2Utd2lkdGg9IjEuNSI+PHBhdGggZD0iTTEyIDJIOC42NjdhMy4zMzMgMy4zMzMgMCAxIDAgMCA2LjY2N0gxMnptMCA2LjY2N0g4LjY2N2EzLjMzMyAzLjMzMyAwIDAgMCAwIDYuNjY2SDEyeiIvPjxwYXRoIGQ9Ik0xOC42NjcgMTJBMy4zMzMgMy4zMzMgMCAxIDEgMTIgMTJhMy4zMzMgMy4zMzMgMCAwIDEgNi42NjcgMFptLTEwIDMuMzM0SDEydjMuMzMzYTMuMzMzIDMuMzMzIDAgMSAxLTMuMzMzLTMuMzM0WiIvPjxwYXRoIGQ9Ik0xMiAyaDMuMzMzYTMuMzMzIDMuMzMzIDAgMSAxIDAgNi42NjdIMTJ6Ii8+PC9nPjwvc3ZnPg==" width="32" height="32" x="351.4222997131112" y="-17.703708685546587" >
                    <animate attributeName="x" values="351.4222997131112;468.4085080994506" dur="10s" repeatCount="indefinite" begin="1.8s"/>
                    <animate attributeName="y" values="-17.703708685546587;418.8947647971123" dur="10s" repeatCount="indefinite" begin="1.8s"/>
                </image>
                <set attributeName="visibility" to="visible" begin="1.8s"/>
            </g>

            <!-- fluent-emoji-flat:panda Meteor -->
            <g filter="url(#meteorGlow)" visibility="hidden">
                <line x1="100.59196534733722" y1="-50" x2="113.53291760246326" y2="-1.7037086855465873" stroke="url(#trail-1780135550646)" stroke-width="2" stroke-linecap="round">
                    <animate attributeName="x1" values="100.59196534733722;217.57817373367658" dur="10s" repeatCount="indefinite" begin="9.8s"/>
                    <animate attributeName="y1" values="-50;386.5984734826589" dur="10s" repeatCount="indefinite" begin="9.8s"/>
                    <animate attributeName="x2" values="113.53291760246326;230.5191259888026" dur="10s" repeatCount="indefinite" begin="9.8s"/>
                    <animate attributeName="y2" values="-1.7037086855465873;434.8947647971123" dur="10s" repeatCount="indefinite" begin="9.8s"/>
                </line>
                <image href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMzIgMzIiPjxnIGZpbGw9Im5vbmUiPjxwYXRoIGZpbGw9IiM0MzNCNkIiIGQ9Ik0zLjQ2MyAxMi43OTVhNC41IDQuNSAwIDEgMSA2LjY0LTYuMDI3QTE0LjQgMTQuNCAwIDAgMSAxNi4wMjkgNS41YzIuMTEgMCA0LjExNi40NTMgNS45MjUgMS4yNjdhNC41IDQuNSAwIDEgMSA2LjY0MiA2LjAyN2ExNC41NiAxNC41NiAwIDAgMSAxLjkzMyA3LjI3NmMwIDQuMDQ5LTEuNjUgNi43LTQuMzQ1IDguMzA4Yy0yLjY1MSAxLjU4MS02LjI2MSAyLjEyMi0xMC4xNTUgMi4xMjJzLTcuNTA0LS41NC0xMC4xNTUtMi4xMjJjLTIuNjk1LTEuNjA4LTQuMzQ1LTQuMjYtNC4zNDUtOC4zMDhjMC0yLjY0OS43MDQtNS4xMzQgMS45MzUtNy4yNzUiLz48cGF0aCBmaWxsPSIjRjRGNEY0IiBkPSJNMi41MjggMjAuMDdjMC03LjQ5NSA2LjA0OC0xMy41NyAxMy41LTEzLjU3czEzLjUgNi4wNjYgMTMuNSAxMy41N2MwIDMuNzIxLTEuNDg1IDYuMDM0LTMuODU4IDcuNDVjLTIuNDE2IDEuNDQtNS44MDYgMS45OC05LjY0MiAxLjk4cy03LjIyNi0uNTQtOS42NDMtMS45OGMtMi4zNzItMS40MTYtMy44NTctMy43MjktMy44NTctNy40NSIvPjxwYXRoIGZpbGw9IiM2MzU5OTQiIGQ9Ik03LjgyNSAxOC45MzdhMy42NCAzLjY0IDAgMCAwIDUuMTQgMGEzLjY0IDMuNjQgMCAwIDAgMC01LjE0Yy0xLjQxOC0xLjQxOC0zLjA4Ni0uNzgxLTQuNTA0LjYzNnMtMi4wNTQgMy4wODYtLjYzNiA0LjUwNG0xNi40MDUgMGMxLjQxOC0xLjQxOC43ODItMy4wODYtLjYzNi00LjUwNGMtMS40MTctMS40MTctMy4wODUtMi4wNTQtNC41MDMtLjYzNmEzLjY0IDMuNjQgMCAwIDAgMCA1LjE0YTMuNjQgMy42NCAwIDAgMCA1LjE0IDAiLz48cGF0aCBmaWxsPSIjMUMxQzFDIiBkPSJNMTEuMDI4IDE2YTEgMSAwIDEgMSAyIDB2MWExIDEgMCAxIDEtMiAwem04IDBhMSAxIDAgMSAxIDIgMHYxYTEgMSAwIDEgMS0yIDB6bS0zLjQ3NSA0LjgybC0xLjAxMy0uODM0YS43MTQuNzE0IDAgMCAxIC40NTMtMS4yNjRoMi4wNzRhLjcxMy43MTMgMCAwIDEgLjQ1MyAxLjI2NGwtMS4wMTQuODMzYS43NS43NSAwIDAgMS0uOTUzIDBNMTYuMDI4IDIyYS41LjUgMCAwIDEgLjQ4Ny4zODljLjA4NS4zMzcuMTk2Ljc0NS40MjcgMS4wNzNjLjIxMy4zMDIuNTI3LjUzOCAxLjA4Ni41MzhjLjY1NCAwIDEtLjUzNCAxLTFhLjUuNSAwIDEgMSAxIDBjMCAuODY4LS42NTUgMi0yIDJjLS45MjUgMC0xLjUyOC0uNDMtMS45MDMtLjk2MmEzIDMgMCAwIDEtLjA5Ny0uMTQ4cS0uMDQ1LjA3Ni0uMDk3LjE0OGMtLjM3NS41MzItLjk3OC45NjItMS45MDMuOTYyYy0xLjM0NiAwLTItMS4xMzItMi0yYS41LjUgMCAxIDEgMSAwYzAgLjQ2Ni4zNDUgMSAxIDFjLjU1OSAwIC
---

## 🧑‍💻 About Me

<img align="right" width="380" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

```python
class Vimalathithan:
    name        = "Vimalathithan N"
    degree      = "Computer Science & Engineering"

    stack = [
        "Python", "SQL", "Power BI",
        "Pandas", "NumPy", "scikit-learn",
        "Power BI", "Google Looker Studio", "Figma", "n8n"
    ]

    currently_learning = [
        " Art of Data "
    ]

    fun_fact = "World generate ocean of data daily. Process tiny puddle."

    def motto(self):
        return "Data is the new oil — I'm the refinery."
```

<br clear="right"/>

---

## 🛠️ Tech Stack

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### 📦 Frameworks & Libraries
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

### 📊 BI & Visualization
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Google Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=google&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

### 🧰 Dev Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=flat-square&logo=pycharm&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Google Opal](https://img.shields.io/badge/Google%20Opal-4285F4?style=flat-square&logo=google&logoColor=white)

---
## 🔥 Streak Stats

<div align="center">
  <img src="https://streak-stats.demolab.com?user=VIMALATHITHAN&theme=tokyonight-duo&hide_border=true&background=0D1117&ring=70A5FD&fire=BF91F3&currStreakLabel=70A5FD&sideLabels=38BDAE&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0D1117&border_radius=10"/>
</div>

---

## 🚀 Featured Projects

<div align="center">

| Project | Stack | Highlights |
|:--------|:------|:-----------|
| [**Uber BI Dashboard**](https://github.com/VIMALATHITHAN) | Power BI · Excel · MySQL | Analyzed ride patterns & peak demand hours; interactive dashboards tracking total trips, revenue trends & ride frequency |
| [**Customer Segmentation K-Means**](https://github.com/VIMALATHITHAN) | Python · Pandas · NumPy · scikit-learn | Segmented **800 customers** into **5 behavioral groups**; **9 visualizations** (PCA, radar, heatmaps); automated marketing strategy generator |
| [**Data Cleaner Pro**](https://github.com/VIMALATHITHAN) | Python · Pandas · NumPy · HTML · CSS · JS | Automated CSV/Excel preprocessing; reduced manual cleaning time by **60–80%**; auto date dimensions + data quality scoring with Excel audit reports |

</div>

---

## 🎓 Education

<div align="center">

| Degree | Institution | Year | Score |
|:-------|:------------|:----:|:-----:|
| B.E. Computer Science & Engineering | Bannari Amman Institute of Technology | 2026 | 7.12 CGPA |
| Diploma | N L Polytechnic | 2023 | 85% |
| SSLC | S R T Universal | 2020 | 84% |

</div>

---

## 🏅 Achievements & Certifications

<div align="center">

| | Achievement | Details |
|:-:|:-----------|:--------|
| 📜 | Essential SQL Skills For Data | Analytics Vidhya — Aug 2025 |
| 📜 | Data Analytics Certification | NXTSYNC PVT LTD — Oct 2025 |
| 💡 | Area of Interest — Analytics | Data · Business Intelligence |
| 🤖 | Area of Interest — Automation | n8n · Google Opal workflows |
| 🎨 | Area of Interest — UI/UX | Wireframe & Design Systems |

</div>

---

## 🌱 Currently Learning

```
📊 Business Intelligence → Google Looker Studio · DAX · Advanced Power BI
🤖 AI Automation         → n8n Workflows · Google Opal · Agentic Pipelines
🎨 UI/UX Design          → Figma Systems · Wireframing · Prototyping
🗄️  Databases            → Advanced SQL · Query Optimization · MySQL
```

---

## 📬 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vimalathithan-n)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vimalthithan.n@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling" width="100%"/>
