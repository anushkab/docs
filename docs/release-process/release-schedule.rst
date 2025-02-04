================
Release Schedule
================

OpenDaylight releases twice per year. The six-month cadence is designed to
synchronize OpenDaylight releases with OpenStack and OPNFV releases. Dates
are adjusted to match current resources and requirements from the current
OpenDaylight users. Dates are also adjusted when they conflict with holidays,
overlap with other releases or are otherwise problematic. Dates include the
release of both managed and self-managed projects.

.. list-table::
   :widths: 20 20 20 20 20 40
   :header-rows: 1
   :stub-columns: 1

   * - **Event**
     - **Sodium Dates**
     - **Magnesium Dates**
     - **Relative Dates**
     - **Start-Relative Dates**
     - **Description**

   * - Release Start
     - 2019-03-07
     - 2019-09-09
     - Start Date
     - Start Date +0
     - Declare Intention: Submit **Project_Plan** Jira item in TSC project

   * - Initial Checkpoint
     - 2019-03-21
     - 2019-09-23
     - Start Date + 2 weeks
     - Start Date +2 weeks
     - Initial Checkpoint. All Managed Projects must have completed
       **Project_Plan** Jira items in TSC project.

   * - Release Integrated Deadline
     - 2019-04-11
     - 2019-10-07
     - Initial Checkpoint + 2 weeks
     - Start Date +4 weeks
     - Deadline for Release Integrated Projects (currently, ODLPARENT,
       YANGTOOLS and MDSAL) to provide the desired version deliverables for
       downstream Snapshot Integrated Projects to consume.
       For Sodium, this is +1 more week to resolve conflict with ONS NA 2019.

   * - Version Bump
     - 2019-04-12
     - 2019-10-08
     - Release Integrated Deadline + 1 day
     - Start Date +4 weeks 1 day
     - Prepare version bump patches and merge them in (RelEng team). Spend the
       next 2 weeks to get green build for all MSI Projects and a healthy
       distribution.

   * - Version Bump Checkpoint
     - 2019-04-25
     - 2019-10-21
     - Release Integrated Deadline + 2 weeks
     - Start Date +6 weeks
     - Check status of MSI Projects to see if we have green builds and a
       healthy distribution. Revert the MRI deliverables if deemed necessary.

   * - CSIT Checkpoint
     - 2019-05-09
     - 2019-11-04
     - Version Bump Checkpoint + 2 weeks
     - Start Date +8 weeks
     - All Managed Release CSIT should be in good shape - get all MSI Projects'
       CSIT results as they were before the version bump. This is the final
       opportunity to revert the MRI deliverables if deemed necessary.

   * - Middle Checkpoint
     - 2019-07-04
     - 2020-01-06
     - CSIT Checkpoint + 8 weeks (sometimes +2 weeks to avoid December holidays)
     - Start Date +16 weeks (sometimes +2 weeks to avoid December holidays)
     - Checkpoint for status of Managed Projects - especially Snapshot
       Integrated Projects.

   * - Code Freeze
     - 2019-08-01
     - 2020-02-03
     - Middle Checkpoint + 4 weeks
     - Start Date +20 weeks
     - Code freeze for all Managed Projects - cut and lock release branch. Only
       allow blocker bugfixes in release branch.

   * - Final Checkpoint
     - 2019-08-15
     - 2020-02-17
     - Code Freeze + 2 weeks
     - Start Date +22 weeks
     - Final Checkpoint for all Managed Projects.

   * - Formal Release
     - 2019-09-05
     - 2020-03-09
     - 6 months after Start Date
     - Start Date +6 months
     - Formal release

   * - Service Release 1
     - 2019-10-17
     - 2020-04-20
     - 1.5 month after Formal Release
     - Start Date +7.5 months
     - Service Release 1 (SR1)

   * - Service Release 2
     - 2020-01-16
     - 2020-07-20
     - 3 months after SR1
     - Start Date +10.5 months
     - Service Release 2 (SR2)

   * - Service Release 3
     - 2020-05-07
     - 2020-11-16
     - 4 months after SR2
     - Start Date +14 months
     - Service Release 3 (SR3) - Final Service Release

   * - Service Release 4
     - N/A
     - N/A
     - Not Available Anymore
     - Not Available Anymore
     - Service Release 4 (SR4) - N/A

   * - Release End of Life
     - 2020-09-05
     - 2021-03-08
     - 4 months after SR3
     - Start Date +18 months
     - End of Life - coincides with the Formal Release of the current release+2
       versions and the start of the current release+3 versions
