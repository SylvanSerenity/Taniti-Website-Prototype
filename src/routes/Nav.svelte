<nav>
	<ul class="nav-section">
		<li class="nav-item"><a href="/"><img src="/logo.png" alt="Taniti"></a></li>
		<li class="nav-item"><a class="nav-link" href="/about">About</a></li>
		<li class="nav-item dropdown">
			<span class="nav-link">Travel</span>
			<ul class="dropdown-menu">
				<li class="nav-item"><a href="/lodging">Lodging</a></li>
				<li class="nav-item"><a href="/transportation">Transportation</a></li>
				<li class="nav-item"><a href="/restaurants">Restaurants</a></li>
			</ul>
		</li>
		<li class="nav-item dropdown">
			<span class="nav-link">Activities</span>
			<ul class="dropdown-menu">
				<li class="nav-item"><a href="/entertainment">Entertainment</a></li>
				<li class="nav-item"><a href="/sightseeing">Sightseeing</a></li>
			</ul>
		</li>
		<li class="nav-item"><a href="/faq">FAQ</a></li>
	</ul>
</nav>

<style>
	nav {
		top: 0;
		position: fixed;
		z-index: 100;
		width: 100%;
		height: var(--nav-height);

		display: flex;
		align-items: center;
		justify-content: center;

		background-color: forestgreen;
		color: white;
	}

	nav * {
		padding: 0;
	}
	nav ul {
		list-style: none;
	}
	nav a {
		text-decoration: none;
		color: white;
	}

	.nav-section {
		height: 100%;

		display: flex;
		justify-content: space-between;
	}

	.nav-item {
		margin-rigt: 5px;
		padding: 10px;
		height: 100%;

		display: flex;
		align-items: center;
	}
	.nav-link {
		position: relative;
		cursor: pointer;
		padding-bottom:2px;
	}
	.nav-link::after {
		position: absolute;
		left: 50%;
		bottom: 0;
		width: 0;
		height: 2px;

		background-color: white;
		transition: width 0.3s ease, left 0.3s ease;
		content: '';
	}
	.nav-item::hover .nav-link::after, .nav-link:hover::after {
		width: 100%;
		left: 0;
	}

	.dropdown {
		height: 100%;

		display: flex;
		align-items: center;

		-webkit-user-select: none;
		-ms-user-select: none;
		user-select: none;
	}
	.dropdown-menu {
		position: absolute;
		margin-left: -10px;

		display: none;

		box-shadow: 2px 2px 5px 0px rgba(0, 0, 0, 0.2);
	}

	@media screen and (min-width: 480px) {
		.dropdown:hover {
			width: 110px;
		}
	}
	.dropdown:hover .dropdown-menu {
		position: fixed;
		top: var(--nav-height);

		display: block;
		background-color: forestgreen;
	}
	.dropdown-menu .nav-item {
		margin: 0;
	}
	.dropdown-menu .nav-item:hover {
		background-color: rgba(0, 0, 0, 0.2);
	}
</style>
