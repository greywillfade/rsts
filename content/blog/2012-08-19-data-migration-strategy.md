---
title: Data migration strategy
description: A very important part of many website builds, and one which is often overlooked, is the migration of existing data or the population of new content.
author: Sally
type: post
date: 2012-08-19T14:52:37+00:00
url: /blog/2012/08/19/data-migration-strategy/
headerimg: /img/content/blog/l/move.jpg
class: bi-2
categories:
  - General
tags:
  - strategy

---
A very important part of many website builds, and one which is often overlooked, is the migration of existing data or the population of new content.

If all of your content is going to be created from scratch it's best to establish upfront how best to standardise the collection of the required data. Spreadsheets following predefined formats can be imported through automation relatively easily, or perhaps, depending on timescales, content can be written straight into a content management system.

When dealing with the migration of existing content, a variety of scenarios may be encountered. In the web arena, these may commonly include moving from a legacy CMS system or blogging engine to a new one, but wanting to keep all existing content and image assets. Another common scenario may be a move from one email marketing service to another, where a database of contacts needs to be transferred along with any lists or reports that have been created.

In order to establish the tasks that need to happen, the responsibilities around who these should be assigned to and the timescales involved, it's important to do some initial technical strategy around the existing system and the proposed new solution.

## Planning the migration

Getting access to the existing data is the first step in planning any migration. This will allow analysis of the systems and versions of software currently used, how data is stored, the data structures involved, identification of the context of fields, and the relationships between data items. There may be a database to review, APIs, or migration may require investigation into a variety of data sources, potentially including offline sources. Once these elements are understood, logical mappings can be created between the old and the new.

Establishing how often the data is updated, by whom and when can be used to help plan the timing of a migration. It is likely that downtime will need to be involved in order to put a freeze on the data in the old system, and this will need to be carefully timed around the switchover to the new system, as well as any tasks which may need to be performed by business users. If the system is critical for end users, offers a service, or downtime may result in lost revenue, migration activities need to be carefully managed. In order to establish how long a migration is likely to take data can be segmented, a small test can be run and timings extrapolated, or a full trial run can be performed. Timeouts, badly formatted data, duplication issues and other exceptions should all be considered.

The migration itself may take certain forms. Certain systems may have export tools available to help select the data required and to output it in a format defined by the user, or the system to be imported into may have import tools of its own. It is important to establish what these tools can do - prebuilt systems will save you developing your own export/import tool and will likely take care of the most common requirements, however it is important to assess these against your individual requirements.

If it is not possible to use an existing tool, the next approach should be consider how much of the process you are able to automate. Understanding the logical mappings established in the initial planning can help to match whether scripts can be created to cover the majority of tasks, or whether any of the migration may have to be done manually. This is not ideal, and depending on the volume of data this can be an incredibly time consuming, labour intensive task, but may be the best or only way to approach certain scenarios, particularly those which involve the migration of data currently not in a suitable format.

The migration itself is one element, but the impact of changing data sources also needs to be considered. When discussed in the context of the web, any changes in the way that content is structured needs to have care taken to maintain SEO. A series of 301 redirects will likely be needed as a bare minimum. If this is something you're interested in please drop my colleague (and SEO/data wizard) <a href="http://www.darrenware.com/" target="_blank">Darren Ware</a> a line.

Once the migration has been performed the system will need to run through a series of audits and tests in order to establish the success of the migration and the acceptance of the new solution. These can involve sense checks (based on the expected number of records, format of data etc), comparison between new data sets and the old, and human checks to ensure that data is not only logical but that it meets any requirements set out prior to the migration. It is advised that a backup of the old data is kept for a suitable length of time (based on current data retention policies) in case problems are found once the old system is decommissioned.
