<form>
	<div class="flow">
		<div class="form-group">
			<label for="first">First Name</label>
			<input
				type="first"
				id="first"
				name="first"
				placeholder="Enter first name..."
				required
			/>
		</div>

		<div class="form-group">
			<label for="last">Last Name</label>
			<input
				type="last"
				id="last"
				name="last"
				placeholder="Enter last name..."
				required
			/>
		</div>

		<div class="form-group">
			<label for="email">Email</label>
			<input
				type="email"
				id="email"
				name="email"
				placeholder="Enter email address..."
				required
			/>
		</div>

		<div class="form-group">
			<label for="tel">Phone (Optional)</label>
			<input type="tel" id="tel" name="tel" placeholder="Enter phone number..." />
		</div>

		<div class="form-group">
			<label for="message">Message</label>
			<textarea name="message" id="message" rows="10" required></textarea>
		</div>

		<button type="submit" class="bg-blue white">Submit Message</button>
	</div>
</form>

<style>
	form {
		max-width: 32rem;
	}

	.form-group {
		display: grid;
	}

	input,
	textarea {
		padding: 1rem;
		font: inherit;
	}

	button:hover {
		background-image: var(--gradient-pink);
	}
</style>
