import { Card } from '../components/Card'

# Card Component

Below is an example of a card with markdown content.

<Card>
  ## This heading won't render as markdown
  - This list item won't render either
  - Neither will this one
  **Bold text** won't work inside JSX without blank lines.
</Card>

Use blank lines around markdown inside JSX to fix this.
