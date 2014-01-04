export PATH=$PATH:~/android-sdks/tools
export PATH=$PATH:~/android-sdks/platform-tools
export ANDROID_HOME=~/android-sdks
export PATH=$PATH:~/bin
### Added by the Heroku Toolbelt
export PATH="/usr/local/heroku/bin:$PATH"
. libs/z.sh
function precmd () {
_z --add "$(pwd -P)"
}
function server() {
	local port="${1:-8000}"
	open "http://localhost:${port}/*"
	python -m SimpleHTTPServer "$port"
}