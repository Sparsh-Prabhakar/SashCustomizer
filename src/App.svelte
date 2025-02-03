<head>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<title>Customer Details</title>
</head>

<body>
	<div class="container-head">
		<h1 style="text-align: center">Sash Customizer</h1>
	</div>
	<div class="form-row">
		<div class="container">
			<h2>Customer Details</h2>
			<form>
				<div class="form-row">
					<div class="form-element">
						<label for="name">Full Name</label>
						<input type="text" id="name" name="name" required />
					</div>
					<div class="form-element">
						<label for="contact">Contact No</label>
						<input type="tel" id="contact" name="contact" required />
					</div>
					<div class="form-element">
						<label for="email">Email ID</label>
						<input type="email" id="email" name="email" required />
					</div>
				</div>
				<div class="form-row">
					<div class="form-element">
						<label for="order-date">Order Date</label>
						<input type="date" id="order-date" name="order-date" required />
					</div>
					<div class="form-element">
						<label for="pickup-date">Pickup Date</label>
						<input type="date" id="pickup-date" name="pickup-date" required />
					</div>
				</div>
			</form>
		</div>
		<!-- <div class="container">
			<h2>Sash Customization</h2>
			<form>
				<div class="form-row">
          <input type="radio" id="html" name="shield_type" value="shield" style="width: 3.5%" />
          <label for="shield" style="margin-top: 2px">Shield</label>
          <input type="radio" id="html" name="shield_type" value="logo" style="width: 3.5%" />
          <label for="logo" style="margin-top: 2px">Logo</label>
				</div>
        <br>
        <br>
				<div style="padding-top: 5px" class="form-row">
          <div>
            <label for="template">Choose a template:</label>
            <select name="template">
              <option>Template 1</option>
              <option>Template 1</option>
              <option>Template 1</option>
              <option>Template 1</option>
            </select>
          </div>
        </div>
			</form>
		</div> -->
	</div>
</body>
