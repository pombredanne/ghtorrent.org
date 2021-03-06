---
layout: page
title: Downloads
tagline:
---

### What am I downloading?

* The MySQL dump is a full, up to date database dump. You can use it for querying the latest available data.
* The MongoDB dumps are incremental. They are provided mostly for reference and backup purposes, as they may contain duplicates. The reasons for this are the following:
  * When refreshing project data, old records are deleted and new are added. This cannot be reflected in the dumps (it is not practical to regenerate all dumps every time).
  * The dumps have already been restored once, hence the dump dates do not
represent the actual data generation dates.
* You can verify the downloaded dumps using SHA256. Here are the signatures: [SHA256SUM](/downloads/SHA256SUM)

For those reasons, we recommend using the MongoDB data through our [query
service](http://ghtorrent.org/raw.html).

### MySQL database dumps
<button type="button" class="btn btn-success">New!</button> As of MySQL dump
`mysql-2015-09-25`, we are distributing CSV files (one file per table) instead
of `mysqldump` based backups. The provided archive expands to a directory
including a restore script and instructions on how to do the restore. See more
information [here](https://github.com/gousiosg/github-mirror/tree/master/sql).

You can also [query MySQL](/dblite). It is always loaded with the latest
dump.

* [2013-10-12](/downloads/mysql-2013-10-12.sql.gz)
* [2014-01-02](/downloads/mysql-2014-01-02.sql.gz)
* [2014-04-02](/downloads/mysql-2014-04-02.sql.gz)
* [2014-08-18](/downloads/mysql-2014-08-18.sql.gz)
* [2014-11-10](/downloads/mysql-2014-11-10.sql.gz)
* [2015-01-04](/downloads/mysql-2015-01-04.sql.gz)
* [2015-04-01](/downloads/mysql-2015-04-01.sql.gz)
* [2015-09-25](/downloads/mysql-2015-09-25.tar.gz)

### Available Downloads
List of available downloads (Last dump date: 2015-03-29)
<table class="table table-hover table-condensed">
<thead>
<tr>
<th>Dump date</th>
<th>commit comments</th>
<th>commits</th>
<th>events</th>
<th>followers</th>
<th>forks</th>
<th>issue comments</th>
<th>issue events</th>
<th>issues</th>
<th>org members</th>
<th>pull request comments</th>
<th>pull requests</th>
<th>repo collaborators</th>
<th>repo labels</th>
<th>repos</th>
<th>users</th>
<th>watchers</th>
</tr>
</thead>
<tbody>
<tr>
<td>2012-03-30</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2012-03-30.tar.gz">810 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2012-03-30.tar.gz">1221 MB</a>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td>2012-05-30</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2012-05-30.tar.gz">17962 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2012-05-30.tar.gz">1945 MB</a>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td>2012-07-30</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2012-07-30.tar.gz">1 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2012-07-30.tar.gz">34533 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2012-07-30.tar.gz">1951 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2012-07-30.tar.gz">35 MB</a>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2012-07-30.tar.gz">18 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2012-07-30.tar.gz">29 MB</a>
</td>
<td>
</td>
</tr>
<tr>
<td>2012-09-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2012-09-29.tar.gz">2 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2012-09-29.tar.gz">10351 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2012-09-29.tar.gz">320 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2012-09-29.tar.gz">15 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2012-09-29.tar.gz">40 MB</a>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/org_members-dump.2012-09-29.tar.gz">1 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2012-09-29.tar.gz">8 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2012-09-29.tar.gz">11 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2012-09-29.tar.gz">34 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2012-09-29.tar.gz">16 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2012-09-29.tar.gz">194 MB</a>
</td>
</tr>
<tr>
<td>2012-11-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2012-11-29.tar.gz">3 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2012-11-29.tar.gz">11921 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2012-11-29.tar.gz">3702 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2012-11-29.tar.gz">13 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2012-11-29.tar.gz">34 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2012-11-29.tar.gz">155 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2012-11-29.tar.gz">84 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2012-11-29.tar.gz">331 MB</a>
</td>
<td>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2012-11-29.tar.gz">8 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2012-11-29.tar.gz">14 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2012-11-29.tar.gz">60 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2012-11-29.tar.gz">7 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2012-11-29.tar.gz">132 MB</a>
</td>
</tr>
<tr>
<td>2013-01-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2013-01-29.tar.gz">8 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2013-01-29.tar.gz">32483 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2013-01-29.tar.gz">3484 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2013-01-29.tar.gz">59 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2013-01-29.tar.gz">211 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2013-01-29.tar.gz">385 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2013-01-29.tar.gz">172 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2013-01-29.tar.gz">328 MB</a>
</td>
<td>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2013-01-29.tar.gz">49 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2013-01-29.tar.gz">70 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2013-01-29.tar.gz">617 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2013-01-29.tar.gz">40 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2013-01-29.tar.gz">256 MB</a>
</td>
</tr>
<tr>
<td>2013-03-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2013-03-29.tar.gz">6 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2013-03-29.tar.gz">64408 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2013-03-29.tar.gz">4530 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2013-03-29.tar.gz">24 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2013-03-29.tar.gz">164 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2013-03-29.tar.gz">257 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2013-03-29.tar.gz">54 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2013-03-29.tar.gz">219 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2013-03-29.tar.gz">22 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2013-03-29.tar.gz">458 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2013-03-29.tar.gz">12 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2013-03-29.tar.gz">1254 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2013-03-29.tar.gz">32 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2013-03-29.tar.gz">74 MB</a>
</td>
</tr>
<tr>
<td>2013-05-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2013-05-29.tar.gz">4 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2013-05-29.tar.gz">30935 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2013-05-29.tar.gz">5083 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2013-05-29.tar.gz">24 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2013-05-29.tar.gz">160 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2013-05-29.tar.gz">236 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2013-05-29.tar.gz">57 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2013-05-29.tar.gz">221 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2013-05-29.tar.gz">6 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2013-05-29.tar.gz">189 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2013-05-29.tar.gz">12 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2013-05-29.tar.gz">492 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2013-05-29.tar.gz">26 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2013-05-29.tar.gz">68 MB</a>
</td>
</tr>
<tr>
<td>2013-07-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2013-07-29.tar.gz">4 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2013-07-29.tar.gz">53606 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2013-07-29.tar.gz">5297 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2013-07-29.tar.gz">21 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2013-07-29.tar.gz">181 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2013-07-29.tar.gz">291 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2013-07-29.tar.gz">60 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2013-07-29.tar.gz">233 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2013-07-29.tar.gz">238 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2013-07-29.tar.gz">245 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2013-07-29.tar.gz">9 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2013-07-29.tar.gz">7 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2013-07-29.tar.gz">586 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2013-07-29.tar.gz">29 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2013-07-29.tar.gz">75 MB</a>
</td>
</tr>
<tr>
<td>2013-09-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2013-09-29.tar.gz">4 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2013-09-29.tar.gz">33317 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2013-09-29.tar.gz">5900 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2013-09-29.tar.gz">33 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2013-09-29.tar.gz">174 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2013-09-29.tar.gz">482 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2013-09-29.tar.gz">67 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2013-09-29.tar.gz">246 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2013-09-29.tar.gz">84 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2013-09-29.tar.gz">880 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2013-09-29.tar.gz">11 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2013-09-29.tar.gz">1 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2013-09-29.tar.gz">530 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2013-09-29.tar.gz">26 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2013-09-29.tar.gz">67 MB</a>
</td>
</tr>
<tr>
<td>2013-11-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2013-11-29.tar.gz">75 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2013-11-29.tar.gz">91654 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2013-11-29.tar.gz">7161 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2013-11-29.tar.gz">33 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2013-11-29.tar.gz">225 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2013-11-29.tar.gz">467 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2013-11-29.tar.gz">91 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2013-11-29.tar.gz">368 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2013-11-29.tar.gz">107 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2013-11-29.tar.gz">49 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2013-11-29.tar.gz">20 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2013-11-29.tar.gz">2 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2013-11-29.tar.gz">847 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2013-11-29.tar.gz">43 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2013-11-29.tar.gz">110 MB</a>
</td>
</tr>
<tr>
<td>2014-01-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2014-01-29.tar.gz">34 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2014-01-29.tar.gz">65615 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2014-01-29.tar.gz">6582 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2014-01-29.tar.gz">204 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2014-01-29.tar.gz">434 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2014-01-29.tar.gz">103 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2014-01-29.tar.gz">376 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2014-01-29.tar.gz">101 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2014-01-29.tar.gz">49 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2014-01-29.tar.gz">16 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2014-01-29.tar.gz">2 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2014-01-29.tar.gz">749 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2014-01-29.tar.gz">32 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2014-01-29.tar.gz">129 MB</a>
</td>
</tr>
<tr>
<td>2014-03-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2014-03-29.tar.gz">40 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2014-03-29.tar.gz">81985 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2014-03-29.tar.gz">8215 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2014-03-29.tar.gz">1 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2014-03-29.tar.gz">259 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2014-03-29.tar.gz">574 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2014-03-29.tar.gz">113 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2014-03-29.tar.gz">372 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2014-03-29.tar.gz">170 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2014-03-29.tar.gz">4180 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2014-03-29.tar.gz">22 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2014-03-29.tar.gz">2 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2014-03-29.tar.gz">918 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2014-03-29.tar.gz">40 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2014-03-29.tar.gz">185 MB</a>
</td>
</tr>
<tr>
<td>2014-05-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2014-05-29.tar.gz">37 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2014-05-29.tar.gz">72305 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2014-05-29.tar.gz">8744 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2014-05-29.tar.gz">73 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2014-05-29.tar.gz">209 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2014-05-29.tar.gz">435 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2014-05-29.tar.gz">83 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2014-05-29.tar.gz">433 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2014-05-29.tar.gz">167 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2014-05-29.tar.gz">533 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2014-05-29.tar.gz">43 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2014-05-29.tar.gz">24 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2014-05-29.tar.gz">647 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2014-05-29.tar.gz">34 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2014-05-29.tar.gz">710 MB</a>
</td>
</tr>
<tr>
<td>2014-07-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2014-07-29.tar.gz">42 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2014-07-29.tar.gz">119560 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2014-07-29.tar.gz">8966 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2014-07-29.tar.gz">95 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2014-07-29.tar.gz">32 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2014-07-29.tar.gz">592 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2014-07-29.tar.gz">106 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2014-07-29.tar.gz">373 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/org_members-dump.2014-07-29.tar.gz">16 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2014-07-29.tar.gz">187 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2014-07-29.tar.gz">640 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2014-07-29.tar.gz">132 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2014-07-29.tar.gz">92 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2014-07-29.tar.gz">539 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2014-07-29.tar.gz">44 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2014-07-29.tar.gz">267 MB</a>
</td>
</tr>
<tr>
<td>2014-09-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2014-09-29.tar.gz">38 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2014-09-29.tar.gz">66774 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2014-09-29.tar.gz">10484 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2014-09-29.tar.gz">25 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2014-09-29.tar.gz">515 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2014-09-29.tar.gz">142 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2014-09-29.tar.gz">356 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2014-09-29.tar.gz">220 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2014-09-29.tar.gz">531 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2014-09-29.tar.gz">85 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2014-09-29.tar.gz">59 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2014-09-29.tar.gz">345 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2014-09-29.tar.gz">25 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2014-09-29.tar.gz">220 MB</a>
</td>
</tr>
<tr>
<td>2014-11-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2014-11-29.tar.gz">39 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2014-11-29.tar.gz">120799 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2014-11-29.tar.gz">10720 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2014-11-29.tar.gz">22 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2014-11-29.tar.gz">577 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2014-11-29.tar.gz">139 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2014-11-29.tar.gz">415 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2014-11-29.tar.gz">215 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2014-11-29.tar.gz">681 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_collaborators-dump.2014-11-29.tar.gz">92 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2014-11-29.tar.gz">82 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2014-11-29.tar.gz">681 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2014-11-29.tar.gz">36 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2014-11-29.tar.gz">232 MB</a>
</td>
</tr>
<tr>
<td>2015-01-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2015-01-29.tar.gz">42 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2015-01-29.tar.gz">121675 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2015-01-29.tar.gz">10628 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2015-01-29.tar.gz">3 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2015-01-29.tar.gz">377 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2015-01-29.tar.gz">708 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2015-01-29.tar.gz">208 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2015-01-29.tar.gz">444 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2015-01-29.tar.gz">358 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2015-01-29.tar.gz">761 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2015-01-29.tar.gz">146 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2015-01-29.tar.gz">1256 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2015-01-29.tar.gz">48 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2015-01-29.tar.gz">255 MB</a>
</td>
</tr>
<tr>
<td>2015-03-29</td>
<td>
<a href="http://ghtorrent.org/downloads/commit_comments-dump.2015-03-29.tar.gz">48 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/commits-dump.2015-03-29.tar.gz">128271 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/events-dump.2015-03-29.tar.gz">12939 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/followers-dump.2015-03-29.tar.gz">90 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/forks-dump.2015-03-29.tar.gz">542 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_comments-dump.2015-03-29.tar.gz">830 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issue_events-dump.2015-03-29.tar.gz">208 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/issues-dump.2015-03-29.tar.gz">520 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/org_members-dump.2015-03-29.tar.gz">2 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_request_comments-dump.2015-03-29.tar.gz">317 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/pull_requests-dump.2015-03-29.tar.gz">937 MB</a>
</td>
<td>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repo_labels-dump.2015-03-29.tar.gz">191 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/repos-dump.2015-03-29.tar.gz">1490 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/users-dump.2015-03-29.tar.gz">53 MB</a>
</td>
<td>
<a href="http://ghtorrent.org/downloads/watchers-dump.2015-03-29.tar.gz">273 MB</a>
</td>
</tr>
</tbody>
</table>
