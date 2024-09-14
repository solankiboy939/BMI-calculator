# BMI-calculator

# Profile Card HTML Example

This is an example of an HTML card with Tailwind CSS for showcasing a profile:

```html
<html></html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com?plugins=forms,typography"></script>
		<script src="https://unpkg.com/unlazy@0.11.3/dist/unlazy.with-hashing.iife.js" defer init></script>
		<script type="text/javascript">
			window.tailwind.config = {
				darkMode: ['class'],
				theme: {
					extend: {
						colors: {
							border: 'hsl(var(--border))',
							input: 'hsl(var(--input))',
							ring: 'hsl(var(--ring))',
							background: 'hsl(var(--background))',
							foreground: 'hsl(var(--foreground))',
							primary: {
								DEFAULT: 'hsl(var(--primary))',
								foreground: 'hsl(var(--primary-foreground))'
							},
							secondary: {
								DEFAULT: 'hsl(var(--secondary))',
								foreground: 'hsl(var(--secondary-foreground))'
							},
							destructive: {
								DEFAULT: 'hsl(var(--destructive))',
								foreground: 'hsl(var(--destructive-foreground))'
							},
							muted: {
								DEFAULT: 'hsl(var(--muted))',
								foreground: 'hsl(var(--muted-foreground))'
							},
							accent: {
								DEFAULT: 'hsl(var(--accent))',
								foreground: 'hsl(var(--accent-foreground))'
							},
							popover: {
								DEFAULT: 'hsl(var(--popover))',
								foreground: 'hsl(var(--popover-foreground))'
							},
							card: {
								DEFAULT: 'hsl(var(--card))',
								foreground: 'hsl(var(--card-foreground))'
							},
						},
					}
				}
			}
		</script>
		<style type="text/tailwindcss">
			@layer base {
				:root {
					--background: 0 0% 100%;
--foreground: 240 10% 3.9%;
--card: 0 0% 100%;
--card-foreground: 240 10% 3.9%;
--popover: 0 0% 100%;
--popover-foreground: 240 10% 3.9%;
--primary: 240 5.9% 10%;
--primary-foreground: 0 0% 98%;
--secondary: 240 4.8% 95.9%;
--secondary-foreground: 240 5.9% 10%;
--muted: 240 4.8% 95.9%;
--muted-foreground: 240 3.8% 46.1%;
--accent: 240 4.8% 95.9%;
--accent-foreground: 240 5.9% 10%;
--destructive: 0 84.2% 60.2%;
--destructive-foreground: 0 0% 98%;
--border: 240 5.9% 90%;
--input: 240 5.9% 90%;
--ring: 240 5.9% 10%;
--radius: 0.5rem;
				}
				.dark {
					--background: 240 10% 3.9%;
--foreground: 0 0% 98%;
--card: 240 10% 3.9%;
--card-foreground: 0 0% 98%;
--popover: 240 10% 3.9%;
--popover-foreground: 0 0% 98%;
--primary: 0 0% 98%;
--primary-foreground: 240 5.9% 10%;
--secondary: 240 3.7% 15.9%;
--secondary-foreground: 0 0% 98%;
--muted: 240 3.7% 15.9%;
--muted-foreground: 240 5% 64.9%;
--accent: 240 3.7% 15.9%;
--accent-foreground: 0 0% 98%;
--destructive: 0 62.8% 30.6%;
--destructive-foreground: 0 0% 98%;
--border: 240 3.7% 15.9%;
--input: 240 3.7% 15.9%;
--ring: 240 4.9% 83.9%;
				}
			}
		</style>
  </head>
  <body>
    <div class="bg-card text-card-foreground p-6 rounded-lg shadow-lg max-w-sm mx-auto">
    <div class="flex items-center mb-4">
        <img src="profile.jpg" alt="Profile Picture" class="rounded-full border-2 border-primary p-1" height="100" width="100">
        <div class="ml-4">
            <h2 class="text-xl font-semibold"><a href="https://www.linkedin.com/in/mr-manohar-solanki/"> Manohar Solanki</a></h2>
            <p class="text-muted-foreground">AI & Data Science Enthusiast | Machine Learning Practitioner | Aspiring Environmental Innovator</p>
        </div>
    </div>
    <p class="text-muted-foreground">Lovely Professional University</p>
    <p class="text-muted-foreground">Jodhpur, Rajasthan, India</p>
    <p class="text-muted-foreground">500k+ connections</p>
    <div class="flex space-x-2 mt-4">
        <button class="bg-secondary text-secondary-foreground hover:bg-secondary/80 px-4 py-2 rounded">Open to work</button>
        <button class="bg-primary text-primary-foreground hover:bg-primary/80 px-4 py-2 rounded">Add section</button>
    </div>
    <div class="mt-6 border-t border-muted">
        <h3 class="text-lg font-semibold mt-4">Analytics</h3>
        <p class="text-muted-foreground">👁️ 2300 profile views</p>
        <p class="text-muted-foreground">📊 700k post impressions</p>
        <p class="text-muted-foreground">Check out who's engaging with your posts.</p>
    </div>
</div>

  </body>
</html>
