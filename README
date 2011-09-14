##TracAccessMacro


The Trac Access macro allows parts of wiki pages to be displayed or hidden depending on the permissions granted to a user viewing the page. It has two variants:

* Make a block of wiki text visible only to users with one of a specified list of permissions.
* Hide a block of wiki text for users with one of a specified list of permissions.


**TracAccessMacro** was created by Jonathan Turkanis
His original version is available at http://trac-hacks.org/wiki/AccessMacro


###Usage

	{{{ 
	#!access
	#allow(TICKET_ADMIN, MILESTONE_ADMIN)
		This is seen only by users with one of the permissions TICKET_ADMIN or 	MILESTONE_ADMIN
	}}}

	{{{
	#!access
	#deny(REPORT_VIEW)
		This is seen only by users who do not have the REPORT_VIEW permission
	}}}

	[[access(deny(REPORT_VIEW), This is an alternate syntax)]]