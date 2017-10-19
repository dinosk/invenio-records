..
    This file is part of Invenio.
    Copyright (C) 2015, 2016 CERN.

    Invenio is free software; you can redistribute it
    and/or modify it under the terms of the GNU General Public License as
    published by the Free Software Foundation; either version 2 of the
    License, or (at your option) any later version.

    Invenio is distributed in the hope that it will be
    useful, but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
    General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with Invenio; if not, write to the
    Free Software Foundation, Inc., 59 Temple Place, Suite 330, Boston,
    MA 02111-1307, USA.

    In applying this license, CERN does not
    waive the privileges and immunities granted to it by virtue of its status
    as an Intergovernmental Organization or submit itself to any jurisdiction.

================
 Invenio-Records
================

.. image:: https://img.shields.io/travis/inveniosoftware/invenio-records.svg
        :target: https://travis-ci.org/inveniosoftware/invenio-records

.. image:: https://img.shields.io/coveralls/inveniosoftware/invenio-records.svg
        :target: https://coveralls.io/r/inveniosoftware/invenio-records

.. image:: https://img.shields.io/github/tag/inveniosoftware/invenio-records.svg
        :target: https://github.com/inveniosoftware/invenio-records/releases

.. image:: https://img.shields.io/pypi/dm/invenio-records.svg
        :target: https://pypi.python.org/pypi/invenio-records

.. image:: https://img.shields.io/github/license/inveniosoftware/invenio-records.svg
        :target: https://github.com/inveniosoftware/invenio-records/blob/master/LICENSE


Invenio-Records is a metadata storage module.
In a few words, a `record`_ is basically a structured collection of fields and
values (metadata) which provides information about other data.

.. _record: https://en.wikipedia.org/wiki/Record_(computer_science)

A record (and each revision) is identified by a unique `UUID`_, as most of the
others entities in Invenio.

.. _UUID: https://en.wikipedia.org/wiki/Universally_unique_identifier

Features:

 * Records creation, update and deletion, with optional schema validation.
 * Version control of record metadata, with revision recovering.
 * CLI and administration interface for CRUD operations on records.
 * Minting PIDs through CLI if `InvenioPIDStore <https://python-jsonschema.readthedocs.io/>`_ is installed.

Further documentation available Documentation: https://invenio-records.readthedocs.io/
