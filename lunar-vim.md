--

-- Set theme e afins --
lvim.colorscheme = "gruvbox"

--

-- atalhos automatizados --

-- Define a margin
vim.opt.colorcolumn = "120"

-- Define o tab e recuo
vim.opt.tabstop = 2
vim.opt.shiftwidth = 2

--

-- Format on save --
lvim.format_on_save.enabled = true

--

-- Plugins --
lvim.plugins = {
  { "ellisonleao/gruvbox.nvim",   priority = 1000 },
  { "marko-cerovac/material.nvim" },
}


--

-- Temas --

-- gruvbox
-- Default options:
-- require("gruvbox").setup({
--   undercurl = true,
--   underline = true,
--   bold = true,
--   italic = {
--     strings = true,
--     comments = true,
--     operators = false,
--     folds = true,
--   },
--   strikethrough = true,
--   invert_selection = false,
--   invert_signs = false,
--   invert_tabline = false,
--   invert_intend_guides = false,
--   inverse = true, -- invert background for search, diffs, statuslines and errors
--   contrast = "",  -- can be "hard", "soft" or empty string
--   palette_overrides = {},
--   overrides = {},
--   dim_inactive = false,
--   transparent_mode = false,
-- })
-- vim.cmd("colorscheme gruvbox")

-- Material contraste
-- vim.g.material_style = "darker"
