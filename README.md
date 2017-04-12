&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![BusyBee Web - metagenomic data analysis by bootstrapped supervised binning and annotation](images/Busybee_web_on_right_side_medium_size_low_res.png)

BusyBee Web (https://ccb-microbe.cs.uni-saarland.de/busybee/) is a web-based, automated, and reference-indepent binning tool for metagenomic data in the form of assembled contigs or long reads (PacBio, Oxford Nanopore Technologies).

**No installation** is required; simply upload your FASTA file and give it a go.
BusyBee Web is based on concepts developed in the context of VizBin and thus tries to combine automated clustering and human inspection into a user-friendly web application.
Moreover, bin quality estimates are provided as complementary means to the visual inspection.
You can optionally enable **taxonomic** annotation using Kraken and the Minikraken database, as well as let BusyBee Web annotate *putative* **antibiotic resistance genes**.
Taxonomic annotation is quick, the functional annotation may take a bit though as genes have to be called first, etc.

[Demo results - 2D scatterplot](images/results.scatterplot_abx.png)
[Demo results - Bin quality estimates table](images/results.bin_quality_table.png)
[Demo results - Taxonomic composition comparison](images/results.taxonomic_composition_compared.png)

# ISSUES
While the web server is principally stable, we are actively working on extending BusyBee Web's functionality.
Moreover, we are curious to see what the load on the server will be.

Should the service be unavailable or should you find that your jobs are waiting in the queue for some time, we would greatly appreciate if you could let us know so we can adjust the hardware requirements accordingly.
Please open a [new issue](https://github.com/claczny/busybee_web/issues/new) in that case.

Should you run into any other issues when using BusyBee Web, please post [an issue](https://github.com/claczny/busybee_web/issues/new) and we will get back to you ASAP.

# TUTORIAL & F.A.Q.s
We provide a [step-by-step tutorial](https://ccb-microbe.cs.uni-saarland.de/busybee/tutorial/) and [F.A.Q.s](https://ccb-microbe.cs.uni-saarland.de/busybee/fqa/).

Should you have questions which are not answered there, just let us know.
A good way to do this is to open a [new issue](https://github.com/claczny/busybee_web/issues/new) describing your question.

# DISCLAIMER
THIS SOFTWARE IS PROVIDED BY THE CHAIR FOR CLINICAL BIOINFORMATICS (SAARLAND UNIVERSITY) AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE CHAIR FOR CLINICAL BIOINFORMATICS (SAARLAND UNIVERSITY) OR ITS CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. 

See also the [About & Disclaimer page](https://ccb-microbe.cs.uni-saarland.de/busybee/about/).

# LOGO
The logo was designed by the hyper-talented Linda Wampach (Twitter: @wampachl).
