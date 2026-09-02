# internshiptrackerrepotest

`listings.json` at the repo root is the real data source for
[ats-scraper](https://github.com/ethancha0/ats-scraper)'s `--ats=github`
poller (see `GITHUB_LISTING_SOURCES` in its `poll.py`) — shaped like
SimplifyJobs' `listings.json` feed. Edit entries there (change an `id`,
bump `date_posted`, flip `active`) to simulate a new posting and see it
flow through `python poll.py --dry-run --ats=github` and into Discord.
The table below is left over from earlier manual testing.

<table>
<tr>
<td><strong><a href="https://example.com">TestCompany</a></strong></td>
<td>Software Intern</td>
<td>Remote</td>
<td><a href="https://example.com">Apply</a></td>
<td>Sept. 2</td>
</tr>




<table>
<tr>
<td><strong><a href="https://example.com">TestCompany</a></strong></td>
<td>Test Role</td>
<td>Remote</td>
<td><a href="https://example.com">Apply</a></td>
<td>Aug 06</td>
</tr>


<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">Barcus</a></strong></td>
<td>testing title2</td>
<td>Irvine, CA</td>
<td><a href="https://youtube.com">Apply</a></td>
<td>Sept. 2</td>
</tr>


<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">Barcus</a></strong></td>
<td>testing title</td>
<td>Irvine, CA</td>
<td><a href="https://youtube.com">Apply</a></td>
<td>Aug 010</td>
</tr>



<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">BELINE</a></strong></td>
<td>testing title</td>
<td>Irvine, CA</td>
<td><a href="https://youtube.com">Apply</a></td>
<td>Aug 010</td>
</tr>




<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">Rtx</a></strong></td>
<td>testing title</td>
<td>Irvine, CA</td>
<td><a href="https://youtube.com">Apply</a></td>
<td>Aug 010</td>
</tr>

<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">Rtx</a></strong></td>
<td>testing title</td>
<td>Irvine, CA</td>
<td><a href="https://youtube.com">Apply</a></td>
<td>Aug 010</td>
</tr>



<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">BULIA</a></strong></td>
<td>A new company</td>
<td>Irvine, CA</td>
<td><a href="https://youtube.com">Apply</a></td>
<td>Aug 010</td>
</tr>


<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">BULIA</a></strong></td>
<td>Software Engineer Intern</td>
<td>Irvine, CA</td>
<td><a href="https://youtube.com">Apply</a></td>
<td>Aug 06</td>
</tr>



<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">ANEWCOMPANY</a></strong></td>
<td>Software Engineer Intern</td>
<td>Irvine, CA</td>
<td><a href="https://youtube.com">Apply</a></td>
<td>Aug 06</td>
</tr>




<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">SecondCompany</a></strong></td>
<td>Software Engineer Intern</td>
<td>Irvine, CA</td>
<td><a href="https://google.com">Apply</a></td>
<td>Aug 06</td>
</tr>


<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">SecondCompany</a></strong></td>
<td>Software Engineer Intern</td>
<td>Irvine, CA</td>
<td><a href="https://google.com">Apply</a></td>
<td>Aug 06</td>
</tr>

<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">SecondCompany</a></strong></td>
<td>Software Engineer Internnnn</td>
<td>Irvine, CA</td>
<td><a href="https://google.com">Apply</a></td>
<td>Aug 06</td>
</tr>


<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">SecondCompany</a></strong></td>
<td>Software Engineer Intern</td>
<td>Irvine, CA</td>
<td><a href="https://google.com">Apply</a></td>
<td>Aug 06</td>
</tr>
<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">SecondCompany</a></strong></td>
<td>Software Engineer Intern</td>
<td>Irvine, CA</td>
<td><a href="https://google.com">Apply</a></td>
<td>Aug 06</td>
</tr>



<!-- New test entry -->
<tr>
<td><strong><a href="https://google.com">SecondCompany</a></strong></td>
<td>Software Engineer Intern</td>
<td>Irvine, CA</td>
<td><a href="https://google.com">Apply</a></td>
<td>Aug 06</td>
</tr>


</table>
