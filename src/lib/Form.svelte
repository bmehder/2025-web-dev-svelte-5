<form>
	<div class="form-wrapper">
		<div class="form-item">
			<label for="first">First Name <span>*</span></label>
			<input
				type="first"
				id="first"
				name="first"
				placeholder="Enter first name..."
				required
			/>
		</div>

		<div class="form-item">
			<label for="last">Last Name <span>*</span></label>
			<input
				type="last"
				id="last"
				name="last"
				placeholder="Enter last name..."
				required
			/>
		</div>

		<div class="form-item">
			<label for="email">Email <span>*</span></label>
			<input
				type="email"
				id="email"
				name="email"
				placeholder="Enter email address..."
				required
			/>
		</div>

		<div class="form-item">
			<label for="tel">Phone (Optional)</label>
			<input type="tel" id="tel" name="tel" placeholder="Enter phone number..." />
		</div>

		<div class="form-item col-span-2">
			<label for="message">Message <span>*</span></label>
			<textarea
				name="message"
				id="message"
				rows="10"
				placeholder="Enter your message..."
				required
			></textarea>
		</div>

		<button type="submit" class="bg-blue white">Submit Message</button>
	</div>
</form>

<style>
	.form-wrapper {
		display: grid;
		gap: 1.5rem;
	}

	@media (width > 40rem) {
		.form-wrapper {
			grid-template-columns: 1fr 1fr;
		}

		.col-span-2 {
			grid-column: span 2;
		}
	}

	.form-item {
		display: grid;
	}

	label {
		font-weight: bold;
	}

	span {
		color: var(--pink);
	}

	input,
	textarea {
		min-width: 0;
		padding: 1rem;
		font: inherit;
	}

	button {
		justify-self: start;
	}

	button:hover {
		background-image: var(--gradient-pink);
	}
</style>
