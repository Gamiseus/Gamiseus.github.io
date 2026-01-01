[data-theme='light'] {
/* Light Theme Colors */
  --color-primary: #6366f1;
  --color-secondary: #8b5cf6;
  --color-background: #ffffff;
  --color-surface: #f9fafb;
  --color-text: #111827;
  --color-text-secondary: #6b7280;
  --color-border: #e5e7eb;
  --color-error: #ef4444;
  --color-warning: #f59e0b;
  --color-success: #10b981;
  --color-info: #3b82f6;

  /* State Colors */
  --color-surface-hover: #f3f4f6;
  --color-primary-hover: #4f46e5;

  /* Compatibility aliases for alternate variable names */
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);

  /* Fonts */
  --font-body: system-ui, -apple-system, sans-serif;
  --font-heading: system-ui, -apple-system, sans-serif;
  --font-mono: 'Monaco', 'Courier New', monospace;

  /* Sizes */
  --font-size: 16px;
  --line-height: 1.6;

  /* Spacing */
  --spacing-xs: 4px;
  --spacing-sm: 8px;
  --spacing-md: 16px;
  --spacing-lg: 24px;
  --spacing-xl: 32px;

  /* Transitions */
  --transition-fast: 150ms ease;
  --transition-normal: 250ms ease;
  --transition-slow: 350ms ease;
}

[data-theme='dark'] {
  /* Dark Theme Colors */
  --color-primary: #818cf8;
  --color-secondary: #a78bfa;
  --color-background: #111827;
  --color-surface: #1f2937;
  --color-text: #f9fafb;
  --color-text-secondary: #9ca3af;
  --color-border: #374151;
  --color-error: #f87171;
  --color-warning: #fbbf24;
  --color-success: #34d399;
  --color-info: #60a5fa;

  /* State Colors */
  --color-surface-hover: #374151;
  /* Lighter than surface (#1f2937) */
  --color-primary-hover: #6366f1;

  /* Compatibility aliases */
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Purple Theme (Vibrant Violet) ==================== */
[data-theme='purple'] {
  /* Colors - Rich violet with electric pink accents */
  --color-primary: #a855f7;
  /* Violet 500 - vibrant purple */
  --color-secondary: #ec4899;
  /* Pink 500 - electric pink accent */
  --color-background: #0d0015;
  /* Ultra deep purple-black */
  --color-surface: #1a0a2e;
  /* Rich purple surface */
  --color-text: #f5f3ff;
  /* Soft lavender white */
  --color-text-secondary: #c4b5fd;
  /* Violet 300 */
  --color-border: #3b2066;
  /* Visible purple border */
  --color-error: #fb7185;
  /* Rose 400 */
  --color-warning: #fbbf24;
  --color-success: #4ade80;
  --color-info: #818cf8;
  /* Indigo 400 */

  /* State Colors */
  --color-surface-hover: #2e1a4a;
  --color-primary-hover: #c084fc;
  /* Violet 400 */

  /* Compatibility aliases */
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Ocean Theme ==================== */
[data-theme='ocean'] {
  /* Colors */
  --color-primary: #06b6d4;
  /* Cyan 500 */
  --color-secondary: #3b82f6;
  /* Blue 500 */
  --color-background: #0f172a;
  /* Slate 900 */
  --color-surface: #1e293b;
  /* Slate 800 */
  --color-text: #f1f5f9;
  --color-text-secondary: #94a3b8;
  --color-border: #334155;
  --color-error: #f87171;
  --color-warning: #fbbf24;
  --color-success: #34d399;
  --color-info: #60a5fa;

  /* State Colors */
  --color-surface-hover: #334155;
  --color-primary-hover: #0891b2;

  /* Compatibility aliases */
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Emerald Theme (Vibrant Green) ==================== */
[data-theme='emerald'] {
  /* Colors - Deep woodland with warm gold accents */
  --color-primary: #4ade80;
  /* Green 400 - fresh leaf */
  --color-secondary: #fbbf24;
  /* Amber 400 - warm gold accent */
  --color-background: #071512;
  /* Very dark forest */
  --color-surface: #0f2920;
  /* Mossy green surface */
  --color-text: #f0fdf4;
  /* Mint white */
  --color-text-secondary: #86efac;
  /* Green 300 */
  --color-border: #14532d;
  /* Green 900 */
  --color-error: #fca5a5;
  /* Red 300 */
  --color-warning: #fcd34d;
  /* Amber 300 */
  --color-success: #4ade80;
  --color-info: #67e8f9;
  /* Cyan 300 */

  /* State Colors */
  --color-surface-hover: #166534;
  /* Green 800 */
  --color-primary-hover: #22c55e;
  /* Green 500 */

  /* Compatibility aliases */
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Mint Theme (Fresh & Clean) ==================== */
[data-theme='mint'] {
  /* Colors - Cool teal-mint with soft aqua accents */
  --color-primary: #2dd4bf;
  /* Teal 400 - fresh mint */
  --color-secondary: #38bdf8;
  /* Sky 400 - light blue accent */
  --color-background: #0f1b1e;
  /* Dark charcoal with teal tint */
  --color-surface: #162328;
  /* Slightly lighter surface */
  --color-text: #f0fdfa;
  /* Very light cyan-white */
  --color-text-secondary: #5eead4;
  /* Teal 300 */
  --color-border: #1e3a3a;
  /* Teal-gray border */
  --color-error: #fca5a5;
  /* Red 300 */
  --color-warning: #fcd34d;
  /* Amber 300 */
  --color-success: #4ade80;
  /* Green 400 */
  --color-info: #67e8f9;
  /* Cyan 300 */

  /* State Colors */
  --color-surface-hover: #1d3d3d;
  --color-primary-hover: #14b8a6;
  /* Teal 500 */

  /* Compatibility aliases */
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}


/* ==================== Forest Theme (Olive & Brown Woodland) ==================== */
[data-theme='forest'] {
  --color-primary: #8fbc8f;
  /* Dark sea green - muted olive */
  --color-secondary: #d4a574;
  /* Warm tan accent */
  --color-background: #1a1814;
  /* Dark brown-olive */
  --color-surface: #2a2820;
  /* Warm olive surface */
  --color-text: #e8e4d9;
  /* Warm cream white */
  --color-text-secondary: #b5ad9e;
  /* Muted tan */
  --color-border: #3d3a30;
  /* Brown-olive border */
  --color-error: #e57373;
  --color-warning: #ffb74d;
  --color-success: #81c784;
  --color-info: #64b5f6;
  --color-surface-hover: #3a3628;
  --color-primary-hover: #a3cca3;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Parchment Theme (Light Typewriter) ==================== */
[data-theme='parchment'] {
  --color-primary: #8b4513;
  /* Saddle brown */
  --color-secondary: #b22222;
  /* Firebrick red accent */
  --color-background: #f5f0e1;
  /* Warm parchment cream */
  --color-surface: #ebe6d5;
  /* Slightly darker cream */
  --color-text: #3d3225;
  /* Dark sepia brown */
  --color-text-secondary: #6b5c4a;
  /* Medium brown */
  --color-border: #d4c9b0;
  /* Light tan border */
  --color-error: #c62828;
  --color-warning: #f57c00;
  --color-success: #2e7d32;
  --color-info: #1565c0;
  --color-surface-hover: #e0dac8;
  --color-primary-hover: #a0522d;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Sepia Theme (Warm Reading Light) ==================== */
[data-theme='sepia'] {
  --color-primary: #5c4033;
  /* Dark brown */
  --color-secondary: #8b6914;
  /* Dark goldenrod */
  --color-background: #f4ecd8;
  /* Warm sepia cream */
  --color-surface: #e8dfc8;
  /* Darker cream */
  --color-text: #3d3225;
  /* Dark sepia */
  --color-text-secondary: #6b5c4a;
  --color-border: #c9bea6;
  --color-error: #c62828;
  --color-warning: #f57c00;
  --color-success: #2e7d32;
  --color-info: #1565c0;
  --color-surface-hover: #ddd4be;
  --color-primary-hover: #7a5a3c;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Nightshade Theme (Dark Purple/Pink) ==================== */
[data-theme='nightshade'] {
  --color-primary: #bd93f9;
  /* Soft purple */
  --color-secondary: #ff79c6;
  /* Pink */
  --color-background: #282a36;
  /* Dark gray-purple */
  --color-surface: #383a4a;
  /* Lighter surface */
  --color-text: #f8f8f2;
  /* Off-white */
  --color-text-secondary: #8be9fd;
  /* Cyan accent text */
  --color-border: #44475a;
  --color-error: #ff5555;
  --color-warning: #f1fa8c;
  --color-success: #50fa7b;
  --color-info: #8be9fd;
  --color-surface-hover: #44475a;
  --color-primary-hover: #d4b8ff;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Nord Theme (Cold & Muted) ==================== */
[data-theme='nord'] {
  --color-primary: #88c0d0;
  /* Frost blue */
  --color-secondary: #81a1c1;
  /* Muted blue */
  --color-background: #2e3440;
  /* Dark gray-blue */
  --color-surface: #3b4252;
  --color-text: #eceff4;
  /* Snow white */
  --color-text-secondary: #d8dee9;
  --color-border: #4c566a;
  --color-error: #bf616a;
  --color-warning: #ebcb8b;
  --color-success: #a3be8c;
  --color-info: #5e81ac;
  --color-surface-hover: #434c5e;
  --color-primary-hover: #8fbcbb;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Monokai Theme (Vibrant Dark) ==================== */
[data-theme='monokai'] {
  --color-primary: #f92672;
  /* Hot pink */
  --color-secondary: #a6e22e;
  /* Lime green */
  --color-background: #272822;
  /* Dark olive */
  --color-surface: #3e3d32;
  --color-text: #f8f8f2;
  --color-text-secondary: #75715e;
  /* Olive comment */
  --color-border: #49483e;
  --color-error: #f92672;
  --color-warning: #e6db74;
  --color-success: #a6e22e;
  --color-info: #66d9ef;
  --color-surface-hover: #49483e;
  --color-primary-hover: #fd5c91;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Gruvbox Theme (Retro Warm) ==================== */
[data-theme='gruvbox'] {
  --color-primary: #fabd2f;
  /* Yellow */
  --color-secondary: #fe8019;
  /* Orange */
  --color-background: #282828;
  /* Dark */
  --color-surface: #3c3836;
  --color-text: #ebdbb2;
  /* Light tan */
  --color-text-secondary: #a89984;
  --color-border: #504945;
  --color-error: #fb4934;
  --color-warning: #fabd2f;
  --color-success: #b8bb26;
  --color-info: #83a598;
  --color-surface-hover: #504945;
  --color-primary-hover: #fabd2f;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Rose Pine Theme (Soft Muted) ==================== */
[data-theme='rosepine'] {
  --color-primary: #ebbcba;
  /* Rose */
  --color-secondary: #c4a7e7;
  /* Iris purple */
  --color-background: #191724;
  /* Dark purple-black */
  --color-surface: #1f1d2e;
  --color-text: #e0def4;
  /* Soft white */
  --color-text-secondary: #908caa;
  --color-border: #26233a;
  --color-error: #eb6f92;
  --color-warning: #f6c177;
  --color-success: #9ccfd8;
  --color-info: #31748f;
  --color-surface-hover: #26233a;
  --color-primary-hover: #f2d5d5;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Tokyo Night Theme (Neon City) ==================== */
[data-theme='tokyo'] {
  --color-primary: #7aa2f7;
  /* Blue */
  --color-secondary: #bb9af7;
  /* Purple */
  --color-background: #1a1b26;
  /* Dark blue-black */
  --color-surface: #24283b;
  --color-text: #c0caf5;
  /* Soft blue-white */
  --color-text-secondary: #565f89;
  --color-border: #414868;
  --color-error: #f7768e;
  --color-warning: #e0af68;
  --color-success: #9ece6a;
  --color-info: #7dcfff;
  --color-surface-hover: #414868;
  --color-primary-hover: #89b4fb;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Cobalt Theme (Deep Blue) ==================== */
[data-theme='cobalt'] {
  --color-primary: #0088ff;
  /* Bright blue */
  --color-secondary: #ff9d00;
  /* Orange accent */
  --color-background: #002240;
  /* Deep cobalt */
  --color-surface: #003366;
  --color-text: #ffffff;
  --color-text-secondary: #80bfff;
  --color-border: #004488;
  --color-error: #ff5a5a;
  --color-warning: #ff9d00;
  --color-success: #3ad900;
  --color-info: #0088ff;
  --color-surface-hover: #004488;
  --color-primary-hover: #3399ff;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Solarized Dark Theme ==================== */
[data-theme='solarized'] {
  --color-primary: #268bd2;
  /* Blue */
  --color-secondary: #2aa198;
  /* Cyan */
  --color-background: #002b36;
  /* Base03 */
  --color-surface: #073642;
  /* Base02 */
  --color-text: #839496;
  /* Base0 */
  --color-text-secondary: #657b83;
  /* Base00 */
  --color-border: #073642;
  --color-error: #dc322f;
  --color-warning: #b58900;
  --color-success: #859900;
  --color-info: #268bd2;
  --color-surface-hover: #094352;
  --color-primary-hover: #2aa198;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Catppuccin Mocha Theme ==================== */
[data-theme='catppuccin'] {
  --color-primary: #cba6f7;
  /* Mauve */
  --color-secondary: #f5c2e7;
  /* Pink */
  --color-background: #1e1e2e;
  /* Base */
  --color-surface: #313244;
  /* Surface0 */
  --color-text: #cdd6f4;
  /* Text */
  --color-text-secondary: #a6adc8;
  /* Subtext0 */
  --color-border: #45475a;
  /* Surface1 */
  --color-error: #f38ba8;
  --color-warning: #f9e2af;
  --color-success: #a6e3a1;
  --color-info: #89b4fa;
  --color-surface-hover: #45475a;
  --color-primary-hover: #ddbdff;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}


/* ==================== Spartan Theme (Halo) ==================== */
[data-theme='spartan'] {
  --color-primary: #5d7c64;
  /* Sage Green */
  --color-secondary: #d4af37;
  /* Visor Gold */
  --color-background: #0d1210;
  /* Dark Armor Green */
  --color-surface: #1a2420;
  /* Lighter Armor */
  --color-text: #e2e8e4;
  /* Off-white */
  --color-text-secondary: #8fa396;
  --color-border: #2c3a32;
  --color-error: #ef4444;
  --color-warning: #d4af37;
  --color-success: #10b981;
  --color-info: #5ec2db;
  /* Cortana Blue */
  --color-surface-hover: #26332d;
  --color-primary-hover: #6e9176;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Night City Theme (Cyberpunk) ==================== */
[data-theme='nightcity'] {
  --color-primary: #fcee0a;
  /* Cyber Yellow */
  --color-secondary: #00f0ff;
  /* Neon Blue */
  --color-background: #050505;
  /* Deep Black */
  --color-surface: #121212;
  /* Grid Dark */
  --color-text: #e0e0e0;
  --color-text-secondary: #9ca3af;
  --color-border: #fcee0a;
  /* Yellow Border */
  --color-error: #ff003c;
  /* Glitch Red */
  --color-warning: #fcee0a;
  --color-success: #39ff14;
  /* Neon Green */
  --color-info: #00f0ff;
  --color-surface-hover: #1a1a1a;
  --color-primary-hover: #e6d909;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Dragonborn Theme (Skyrim) ==================== */
[data-theme='dragonborn'] {
  --color-primary: #77b8c8;
  /* Ice Blue (Constellation) */
  --color-secondary: #ffffff;
  /* Stark White accent */
  --color-background: #141414;
  /* Void */
  --color-surface: #1f2124;
  /* Dark Slate */
  --color-text: #e8e8e8;
  /* High contrast Grey */
  --color-text-secondary: #99aab5;
  --color-border: #40444b;
  --color-error: #cd5c5c;
  --color-warning: #e3c07e;
  --color-success: #77b8c8;
  --color-info: #ffffff;
  --color-surface-hover: #292b30;
  --color-primary-hover: #98d1e0;
  /* Lighter Ice Blue */
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== System Theme (Matrix) ==================== */
[data-theme='system'] {
  --color-primary: #008f11;
  /* Terminal Green */
  --color-secondary: #003b00;
  /* Darker Green */
  --color-background: #020502;
  /* Black Green */
  --color-surface: #051005;
  /* Matrix Surface */
  --color-text: #b0f0b0;
  /* Phosphor Pale Green */
  --color-text-secondary: #00c218;
  /* Brighter Green */
  --color-border: #003b00;
  --color-error: #ff3333;
  --color-warning: #cccc00;
  --color-success: #00ff00;
  --color-info: #008f11;
  --color-surface-hover: #0a1f0a;
  --color-primary-hover: #00b315;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Wasteland Theme (Fallout) ==================== */
[data-theme='wasteland'] {
  --color-primary: #1aff80;
  /* Pip-Boy Green */
  --color-secondary: #114224;
  /* Dark UI */
  --color-background: #080a08;
  /* Screen Off */
  --color-surface: #0f180f;
  /* Scanline Dark */
  --color-text: #ceffce;
  /* Glow White */
  --color-text-secondary: #4ade80;
  /* Dim Green */
  --color-border: #114224;
  --color-error: #ff4444;
  --color-warning: #ffaa00;
  --color-success: #1aff80;
  --color-info: #1aff80;
  --color-surface-hover: #162416;
  --color-primary-hover: #4dff9e;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Commander Theme (Mass Effect) ==================== */
[data-theme='commander'] {
  --color-primary: #c41e3a;
  /* N7 Red */
  --color-secondary: #ffffff;
  /* Alliance White */
  --color-background: #0b0c10;
  /* Space Black */
  --color-surface: #1a1a1d;
  /* Carbon */
  --color-text: #f0f0f0;
  /* Standard White */
  --color-text-secondary: #c5c6c7;
  /* Silver */
  --color-border: #45a29e;
  /* Hologram Blue */
  --color-error: #c41e3a;
  --color-warning: #ff9900;
  /* Omni-tool Orange */
  --color-success: #66fcf1;
  /* Cyan */
  --color-info: #45a29e;
  --color-surface-hover: #26272b;
  --color-primary-hover: #e3264b;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Budapest Theme (Grand Budapest Hotel) ==================== */
[data-theme='budapest'] {
  --color-primary: #784283;
  /* Purple */
  --color-secondary: #F2A478;
  /* Pastel Orange */
  --color-background: #FFF0F5;
  /* Lavender Blush */
  --color-surface: #FFD7E6;
  /* Soft Pink */
  --color-text: #510056;
  /* Dark Purple */
  --color-text-secondary: #9b5580;
  /* Muted Purple */
  --color-border: #de83b2;
  /* Bio Pink */
  --color-error: #e5000c;
  /* Bold Red */
  --color-warning: #ddd690;
  /* Gold */
  --color-success: #4ade80;
  --color-info: #a4d8ff;
  --color-surface-hover: #ffc2d9;
  --color-primary-hover: #91559e;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Arrakis Theme (Dune) ==================== */
[data-theme='arrakis'] {
  --color-primary: #C06C47;
  /* Spice Rust */
  --color-secondary: #4A6D7C;
  /* Water of Life Blue */
  --color-background: #F3E5AB;
  /* Vanilla Sand */
  --color-surface: #E6D690;
  /* Darker Sand */
  --color-text: #3D2B1F;
  /* Dark Brown */
  --color-text-secondary: #8c735a;
  /* Sand Brown */
  --color-border: #d4c4a8;
  --color-error: #c0392b;
  --color-warning: #e67e22;
  --color-success: #27ae60;
  --color-info: #2980b9;
  --color-surface-hover: #decb7b;
  --color-primary-hover: #d35400;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Shire Theme (LotR) ==================== */
[data-theme='shire'] {
  --color-primary: #4C7031;
  /* Hobbit Green */
  --color-secondary: #E6C229;
  /* Sun Gold */
  --color-background: #F9FDF5;
  /* Off-white Green */
  --color-surface: #ECF5E1;
  /* Light Green */
  --color-text: #2F3A23;
  /* Dark Earthy Green */
  --color-text-secondary: #6e7d5e;
  --color-border: #cddbc4;
  --color-error: #c0392b;
  --color-warning: #f39c12;
  --color-success: #4C7031;
  --color-info: #3498db;
  --color-surface-hover: #dbead0;
  --color-primary-hover: #5d873d;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Gatsby Theme (Art Deco) ==================== */
[data-theme='gatsby'] {
  --color-primary: #D4AF37;
  /* Metallic Gold */
  --color-secondary: #000000;
  /* Black Accents */
  --color-background: #FAF9F6;
  /* Off White */
  --color-surface: #F0EEE6;
  /* Cream */
  --color-text: #1A1A1A;
  /* Charcoal */
  --color-text-secondary: #5e5e5e;
  --color-border: #D4AF37;
  /* Gold Border */
  --color-error: #8b0000;
  --color-warning: #D4AF37;
  --color-success: #228b22;
  --color-info: #00008b;
  --color-surface-hover: #e6e3d8;
  --color-primary-hover: #f1c40f;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Her Theme (Soft Warmth) ==================== */
[data-theme='her'] {
  --color-primary: #D93B28;
  /* Shirt Red */
  --color-secondary: #E8927C;
  /* Soft Orange */
  --color-background: #FFF5EE;
  /* Seashell */
  --color-surface: #FDE4D8;
  /* Peach */
  --color-text: #4A2C2A;
  /* Warm Brown */
  --color-text-secondary: #a07a77;
  --color-border: #f2d1c9;
  --color-error: #D93B28;
  --color-warning: #e67e22;
  --color-success: #2ecc71;
  --color-info: #3498db;
  --color-surface-hover: #fad2c3;
  --color-primary-hover: #ff4d4d;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}

/* ==================== Totoro Theme (Ghibli Nature) ==================== */
[data-theme='totoro'] {
  --color-primary: #5D8CAE;
  /* Totoro Grey-Blue */
  --color-secondary: #A6D784;
  /* Leaf Green */
  --color-background: #F7EEE9;
  /* Linen White */
  --color-surface: #E8F6F6;
  /* Sky Blue Tint */
  --color-text: #4A5D6A;
  /* Dark Grey Blue */
  --color-text-secondary: #8c9ba5;
  --color-border: #d1dede;
  --color-error: #e74c3c;
  --color-warning: #f1c40f;
  --color-success: #A6D784;
  --color-info: #5D8CAE;
  --color-surface-hover: #d6eded;
  --color-primary-hover: #7aa9cc;
  --bg-primary: var(--color-background);
  --bg-secondary: var(--color-surface);
  --bg-tertiary: var(--color-surface-hover);
  --text-primary: var(--color-text);
  --text-secondary: var(--color-text-secondary);
  --text-tertiary: var(--color-text-secondary);
  --border-color: var(--color-border);
  --accent-color: var(--color-primary);
  --accent-light: var(--color-primary-hover);
  --color-text-muted: var(--color-text-secondary);
  --color-text-dim: var(--color-text-secondary);
  --color-bg-secondary: var(--color-surface);
  --color-bg-secondary-hover: var(--color-surface-hover);
  --color-accent: var(--color-primary);
}