# Disclaimer
This is just a mirror of the orginal project created by arcange and hosted at https://gitlab.syncad.com/hive/hive-net. I have coipied it to clean it slightly and pack it and deployy to nuget.org.

When orginal author will make a decision to deloy the project as a nuget I will delete this repo. 

# Hive.NET

.NET classes to interact with the Hive blockchain and wallet.

## Prerequisites

1. hived 

To communicate with **hived** you need either a local hived node running with rpc-endpoint open or have access to a remote API node.

If you want tp use a local node, check [this guide](https://gitlab.syncad.com/hive/hive/-/blob/master/README.md) for more information on how to do it.

2. cli_wallet
 
To communicate with **cli-wallet** you need a local cli_wallet instance running with rpc-endpoint open
By default, CHiveWallet object will try to connect to host **"127.0.0.1:8091"**

## Quick-Start

Hive.NET API is currently provided in different bundles :

1. Hive.NET **COM library** you can use in any application able talk with COM objects (Apps, Words, Excel, ...)

2. Hive.NET **VB.NET classes** you can integrate in you own Microsoft Visual Studio project

3. Hive.NET **C#.NET classes** you can integrate in you own Microsoft Visual Studio project

## IMPORTANT NOTE

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
