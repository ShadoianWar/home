<html>
    <head>
        <style>
            body, html {
              height: 100%;
              margin: 0;
            }
            .header {
              position: relative;
              text-align: center;
              max-width: 100%;
              color: white;
              background-image: url("https://i.imgur.com/lkLq6un.png");
              height: 50%;
              left: 200px;
              background-position: center;
              background-repeat: no-repeat;
              background-size: cover;
            }
            .hcentered {
              position: absolute;
              top: 50%;
              font-size: 75px;
              font-family: "Times New Roman", Times, serif;
              left: 50%;
              transform: translate(-50%, -50%);
            }
            body {
                background:#333333
            }
        </style>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
			body {
			  margin: 0;
			  font-family: "Lato", sans-serif;
			}
			.sidebar {
			  margin: 0;
			  padding: 0;
			  width: 200px;
			  background-color: #252525;
			  position: fixed;
			  height: 100%;
			  overflow: auto;
			}
			.sidebar a {
			  display: block;
			  color: white;
			  padding: 16px;
			  text-decoration: none;
			}
			.sidebar a.active {
			  background-color: #4CAF50;
			  color: white;
			}
			.sidebar a:hover:not(.active) {
			  background-color: #555;
			  color: white;
			}
			div.content {
			  margin-left: 200px;
			  padding: 1px 16px;
			  height: 1000px;
			}
			@media screen and (max-width: 700px) {
			  .sidebar {
				width: 100%;
				height: auto;
				position: relative;
			  }
			  .header {
                  position: relative;
                  text-align: center;
                  max-width: 100%;
                  color: white;
                  left: 0px;
                  background-image: url("https://i.imgur.com/lkLq6un.png");
                  height: 50%; 
                  background-position: center;
                  background-repeat: no-repeat;
                }

			  .sidebar a {float: left;}
			  div.content {margin-left: 0;}
			}
			@media screen and (max-width: 400px) {
                .header {
                  position: relative;
                  text-align: center;
                  max-width: 100%;
                  color: white;
                  left: 200px;
                  background-image: url("https://i.imgur.com/lkLq6un.png");
                  height: 50%; 
                  background-position: center;
                  background-repeat: no-repeat;
                }
			  .sidebar a {
				text-align: center;
				float: none;
			  }
			}
		</style>
    </head>
    <section>
        <div class="sidebar">
		  <a class="active">Home</a>
		  <a href="#about">About</a>
		  <a href="#team">The Team</a>
		</div>
    </section>
    <section class="header">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <div class="hcentered">The Shadowian War</div>
	</section>
</html>
