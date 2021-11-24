<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
	<foreignObject width="100%" height="100%">
		<div xmlns="http://www.w3.org/1999/xhtml">
			<style>
				@keyframes rotate {
					0% {
						transform: rotate(3deg);
					}
					100% {
						transform: rotate(-3deg);
					}
				}
				@keyframes gradientBackground {
					0% {
						background-position: 0% 50%;
					}
					50% {
						background-position: 100% 50%;
					}
					100% {
						background-position: 0% 50%;
					}
				}
				@keyframes fadeIn {
					0% {
						opacity: 0;
					}
					66% {
						opacity: 0;
					}
					100% {
						opacity: 1;
					}
				}
				.container {
					font-family:
						system-ui,
						-apple-system,
						'Segoe UI',
						Roboto,
						Helvetica,
						Arial,
						sans-serif,
						'Apple Color Emoji',
						'Segoe UI Emoji';
					display: flex;
					flex-direction: column;
					align-items: center;
					justify-content: center;
					margin: 0;
					width: 100%;
					height: 400px;
					background: linear-gradient(-45deg, #fc5c7d, #6a82fb, #05dfd7);
					background-size: 600% 400%;
					animation: gradientBackground 10s ease infinite;
					border-radius: 10px;
					color: white;
					text-align: center;
				}
				h1 {
					font-size: 50px;
					line-height: 1.3;
					letter-spacing: 5px;
					text-transform: uppercase;
					text-shadow:
						0 1px 0 #efefef,
						0 2px 0 #efefef,
						0 3px 0 #efefef,
						0 4px 0 #efefef,
						0 12px 5px rgba(0, 0, 0, 0.1);
					animation: rotate ease-in-out 1s infinite alternate;
				}
				p {
					font-size: 20px;
					text-shadow: 0 1px 0 #efefef;
					animation: 5s ease 0s normal forwards 1 fadeIn;
				}
			</style>
			<div class="container">
				<h1>Made with HTML &amp; CSS<br/>not an animated GIF</h1>
				<p>Click to see the source</p>
			</div>
		</div>
	</foreignObject>
</svg>


<!-- <style>
    table {
        border: 1px solid white;
    }
    th, td {
        align-content: center;
    }
    a {
        font-size: 15px;
        font-weight: bold;
    }
    ol li {
        /* list-style: decimal-leading-zero; */
        font-size:25px;
    }
    li span {
        font-size:15px;
    }
</style>

<ol start="1">
<li><span><a>Extrapolative behavior of ML models</a></span></li>
Some intro here \
Image, Repo, Url, Website, Org, Code

<li><span>

## Automated end-to-end causal inference application </span></li>
Some intro here \
Image, Repo, Url, Website, Org, Code

<li><span>

## Human extrapolative behavioral experiment via web application</span></li>
Some intro here \
Image, Repo, Url, Website, Org, Code

<li><span>

## Probabilistic linkage of real-world hospital data</span></li>
Some intro here \
Image, Repo, Url, Website, Org, Code

<li><span>

## Multivariate time-series hologram biometric signal parsing</span></li>
Some intro here \
Image, Repo, Url, Website, Org, Code

</ol> -->