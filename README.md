# Fussy Fox

_Fussy Fox is a real-time code linting platform for GitHub_

Make your reviews about content and your CI suite about tests.
Let us worry about style 😎

Fussy Fox provides a variety of static code analytic services.
We use AWS Lambda to provide coders with lightning fast feedback on each commit.

![sample](sample.png)

### Setup

The setup is simple. Just add a file config file to your repository specifying
which linters you want to run.

The configuration is stored in a simple YAML format in a file named
`.checks.yml`.

Sample config: `.checks.yml`

```YAML
- bandit
- flake8
- isort
```

### Love

We are happy to add more tools, feel free to suggest some
[over here](https://github.com/FussyFox/fussyfox.github.io/issues).


### Privacy

FussyFox has a very simple yet strict privacy policy to give our users the
security they deserve.

We don't collect or store any information, that is not required to provide an
excellent service. Furthermore we don't store any information longer than
necessary.

As a result, we are not collecting or story any private information for more
then 5 minutes, the max. execution time of a check. We also don't retain server
logs for more than 30 days.

Also all our software is open source, you are welcome to verify that we do good
on those promised and alert us if we made a mistake. In those cases please
reach out to security@johanneshoppe.com

What about **GDPR**? — Since we don't store any information that isn't needed
and never longer than 30 days, we follow the GDRP requirements.

That being said, here comes the boring legal part:

FussyFox further called "the software" is owned by

Johannes Hoppe
Lennéstr. 19
14469 Potsdam
Germany

info@johanneshoppe.com

The software does not store information for more than 30 days. All private
information is only retained for the that that is required to operate the
software.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
