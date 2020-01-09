
module.exports = {
	root: true,
	parserOptions: {
		'parser': 'babel-eslint',
		'ecmaVersion': 2017,
		'ecmaFeatures': {
			experimentalObjectRestSpread: true,
			spread: true,
		},
	},
	env: {
		browser: true,
		es6: true,
	},
	extends: [
		// https://github.com/vuejs/eslint-plugin-vue#priority-a-essential-error-prevention
		// consider switching to `plugin:vue/strongly-recommended` or `plugin:vue/recommended` for stricter rules.
		'eslint:recommended',
		'plugin:vue/recommended',
		// https://github.com/standard/standard/blob/master/docs/RULES-en.md
		'standard',
	],
	// required to lint *.vue files
	plugins: [
		'vue',
		'html',
	],
	// add your custom rules here
	rules: {
		'vue/html-indent': ['error', 'tab', {
			'alignAttributesVertically': true,
		}],
		'no-unneeded-ternary': ['error', {'defaultAssignment': false}],
		// allow paren-less arrow functions
		'arrow-parens': 0,
		// allow async-await
		'generator-star-spacing': 'off',
		// allow debugger during development
		'no-debugger': process.env.NODE_ENV === 'production' ? 'error' : 'off',
		'no-tabs': 0,
		'indent': ['error', 'tab'],
		'quotes': [
			'error',
			'single',
		],
		'semi': [
			'error',
			'never',
		],
		'indent-size': [true, 2],
		'no-mixed-spaces-and-tabs': ['error', 'smart-tabs'],
		'comma-dangle': ['error', 'always-multiline'],
	},
}
