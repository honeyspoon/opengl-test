project(
	'OpenGlTest',
	'cpp',
	default_options: [
		'cpp_std=c++17'
	],
)

gl = dependency('gl')
glfw = dependency('glfw3', version: '>= 3')
glew = dependency('glew')

executable(
	'run',
	['src/main.cpp'],
	dependencies: [
		gl,
		glfw,
		glew
	]
)
