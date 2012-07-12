# FreeImage QNX Port

This is QNX Port for both Playbook and Blackberry 10 for FreeImage. To build it make sure you already sourced the ```bbndk-env.sh``` from the Blackberry Native SDK. To build the library invoke:

```make -f Makefile.qnx```

There will be three files in the ```Dist``` directory:
- ```FreeImage.h``` The FreeImage Header
- ```libfreeimage-x86.a``` FreeImage static library for Simulator
- ```libfreeimage-armv7.a``` FreeImage static library for Device Target

**Repository Committers** 

* [Didiet Noor](https://github.com/lynxluna)

# Upstream Location

Upstream is located at http://freeimage.sourceforge.net/

## Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

