<template>
	<!-- <nav class="navbar navbar-expand-lg navbar-light bg-light">
		<div class="container-fluid">
			

			<div class="collapse navbar-collapse">
				<ul class="navbar-nav me-auto mb-2 mb-lg-0">
					

					
				</ul>
			</div>
		</div>
	</nav> -->

	<nav class="navbar navbar-expand-lg navbar-light bg-light">
		<div class="container-fluid">
			<router-link to="/" class="navbar-brand">Stock Trader</router-link>

			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav me-auto mb-2 mb-lg-0">
					<router-link to="/portfolio" activeClass="active" tag="li"
						><a>Portfolio</a>
					</router-link>

					<router-link to="/stocks" activeClass="active" tag="li">
						<a>Stocks</a>
					</router-link>
				</ul>

				<ul class="navbar-nav">
					<li class="nav-item dropdown">
						<a
							class="nav-link dropdown-toggle"
							href="#"
							id="navbarDropdown"
							role="button"
							data-bs-toggle="dropdown"
							aria-expanded="false"
						>
							Dropdown
						</a>
						<ul
							class="dropdown-menu"
							aria-labelledby="navbarDropdown"
						>
							<li>
								<a class="dropdown-item" href="#">Action</a>
							</li>
							<li>
								<a class="dropdown-item" href="#"
									>Another action</a
								>
							</li>
							<li><hr class="dropdown-divider" /></li>
							<li>
								<a class="dropdown-item" href="#"
									>Something else here</a
								>
							</li>
						</ul>
					</li>
				</ul>
			</div>
		</div>
	</nav>
</template>
