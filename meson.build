project(
	'OpenGlTest',
	'cpp',
	default_options: [
	],
)

gl = dependency('gl')
glfw = dependency('glfw3', version: '>= 3')

executable('run', ['src/main.cpp'], dependencies: [gl, glfw])
