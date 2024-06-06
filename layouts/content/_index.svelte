<script>
	export let title, time, place;
</script>

<h1>{title}</h1>

<div class="details">
	<div class="time">{time}</div>
	<div class="place">
		<a href={place.link} target="blank" rel="noopener noreferrer">{place.text}</a>
	</div>
	<div class="schedule">
		<h3>Schedule</h3>
		<p>11:30</p>
		<p>1:00</p>
		<p>Dinner</p>
	</div>
	<div class="fees">
		<p>Player</p>
		<p>Foursome</p>
		<p>Guest</p>
	</div>
	<div class="venmo">
		<div class="name">Tim</div>
		<div class="handle">@Timothy-Harper-23</div>
		<div class="qr-code">
			<img src="/media/venmo.webp" alt="QR code to pay with venmo" />
		</div>
	</div>
	<div class="checks">
		<div class="payable">
			<strong>Payable To:</strong>
			<div>Timothy Harper</div>
		</div>
		<div class="address">
			<strong>Mail To</strong>
			<div>24 Atkins St</div>
			<div>Chicopee, MA 01013</div>
		</div>
	</div>
	<div class="contact">
		<div>Contact Laura</div>
	</div>
</div>
