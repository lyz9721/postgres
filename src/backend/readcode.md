2024-04-20
├── access
│   ├── common
│   │   ├── heaptuple.c
│   │   ├── indextuple.c
│   │   ├── Makefile
│   │   ├── printtup.c
│   │   ├── reloptions.c
│   │   ├── scankey.c
│   │   └── tupdesc.c
│   ├── gin
│   │   ├── ginarrayproc.c
│   │   ├── ginbtree.c
│   │   ├── ginbulk.c
│   │   ├── gindatapage.c
│   │   ├── ginentrypage.c
│   │   ├── ginfast.c
│   │   ├── ginget.c
│   │   ├── gininsert.c
│   │   ├── ginscan.c
│   │   ├── ginutil.c
│   │   ├── ginvacuum.c
│   │   ├── ginxlog.c
│   │   ├── Makefile
│   │   └── README
│   ├── gist
│   │   ├── gist.c
│   │   ├── gistget.c
│   │   ├── gistproc.c
│   │   ├── gistscan.c
│   │   ├── gistsplit.c
│   │   ├── gistutil.c
│   │   ├── gistvacuum.c
│   │   ├── gistxlog.c
│   │   ├── Makefile
│   │   └── README
│   ├── hash
│   │   ├── hash.c
│   │   ├── hashfunc.c
│   │   ├── hashinsert.c
│   │   ├── hashovfl.c
│   │   ├── hashpage.c
│   │   ├── hashscan.c
│   │   ├── hashsearch.c
│   │   ├── hashsort.c
│   │   ├── hashutil.c
│   │   ├── Makefile
│   │   └── README
│   ├── heap
│   │   ├── heapam.c
│   │   ├── hio.c
│   │   ├── Makefile
│   │   ├── pruneheap.c
│   │   ├── README.HOT
│   │   ├── rewriteheap.c
│   │   ├── syncscan.c
│   │   ├── tuptoaster.c
│   │   └── visibilitymap.c
│   ├── index
│   │   ├── genam.c
│   │   ├── indexam.c
│   │   └── Makefile
│   ├── Makefile
│   ├── nbtree
│   │   ├── Makefile
│   │   ├── nbtcompare.c
│   │   ├── nbtinsert.c
│   │   ├── nbtpage.c
│   │   ├── nbtree.c
│   │   ├── nbtsearch.c
│   │   ├── nbtsort.c
│   │   ├── nbtutils.c
│   │   ├── nbtxlog.c
│   │   └── README
│   └── transam
│       ├── clog.c
│       ├── Makefile
│       ├── multixact.c
│       ├── README
│       ├── recovery.conf.sample
│       ├── rmgr.c
│       ├── slru.c
│       ├── subtrans.c
│       ├── transam.c
│       ├── twophase.c
│       ├── twophase_rmgr.c
│       ├── varsup.c
│       ├── xact.c
│       ├── xlog.c
│       └── xlogutils.c
├── bootstrap
│   ├── bootparse.y
│   ├── bootscanner.l
│   ├── bootstrap.c
│   └── Makefile
├── catalog
│   ├── aclchk.c
│   ├── catalog.c
│   ├── dependency.c
│   ├── genbki.sh
│   ├── heap.c
│   ├── index.c
│   ├── indexing.c
│   ├── information_schema.sql
│   ├── Makefile
│   ├── namespace.c
│   ├── pg_aggregate.c
│   ├── pg_constraint.c
│   ├── pg_conversion.c
│   ├── pg_depend.c
│   ├── pg_enum.c
│   ├── pg_inherits.c
│   ├── pg_largeobject.c
│   ├── pg_namespace.c
│   ├── pg_operator.c
│   ├── pg_proc.c
│   ├── pg_shdepend.c
│   ├── pg_type.c
│   ├── README
│   ├── sql_feature_packages.txt
│   ├── sql_features.txt
│   ├── storage.c
│   ├── system_views.sql
│   └── toasting.c
├── commands
│   ├── aggregatecmds.c
│   ├── alter.c
│   ├── analyze.c
│   ├── async.c
│   ├── cluster.c
│   ├── comment.c
│   ├── conversioncmds.c
│   ├── copy.c
│   ├── dbcommands.c
│   ├── define.c
│   ├── discard.c
│   ├── explain.c
│   ├── foreigncmds.c
│   ├── functioncmds.c
│   ├── indexcmds.c
│   ├── lockcmds.c
│   ├── Makefile
│   ├── opclasscmds.c
│   ├── operatorcmds.c
│   ├── portalcmds.c
│   ├── prepare.c
│   ├── proclang.c
│   ├── schemacmds.c
│   ├── sequence.c
│   ├── tablecmds.c
│   ├── tablespace.c
│   ├── trigger.c
│   ├── tsearchcmds.c
│   ├── typecmds.c
│   ├── user.c
│   ├── vacuum.c
│   ├── vacuumlazy.c
│   ├── variable.c
│   └── view.c
├── common.mk
├── executor
│   ├── execAmi.c
│   ├── execCurrent.c
│   ├── execGrouping.c
│   ├── execJunk.c
│   ├── execMain.c
│   ├── execProcnode.c
│   ├── execQual.c
│   ├── execScan.c
│   ├── execTuples.c
│   ├── execUtils.c
│   ├── functions.c
│   ├── instrument.c
│   ├── Makefile
│   ├── nodeAgg.c
│   ├── nodeAppend.c
│   ├── nodeBitmapAnd.c
│   ├── nodeBitmapHeapscan.c
│   ├── nodeBitmapIndexscan.c
│   ├── nodeBitmapOr.c
│   ├── nodeCtescan.c
│   ├── nodeFunctionscan.c
│   ├── nodeGroup.c
│   ├── nodeHash.c
│   ├── nodeHashjoin.c
│   ├── nodeIndexscan.c
│   ├── nodeLimit.c
│   ├── nodeMaterial.c
│   ├── nodeMergejoin.c
│   ├── nodeNestloop.c
│   ├── nodeRecursiveunion.c
│   ├── nodeResult.c
│   ├── nodeSeqscan.c
│   ├── nodeSetOp.c
│   ├── nodeSort.c
│   ├── nodeSubplan.c
│   ├── nodeSubqueryscan.c
│   ├── nodeTidscan.c
│   ├── nodeUnique.c
│   ├── nodeValuesscan.c
│   ├── nodeWindowAgg.c
│   ├── nodeWorktablescan.c
│   ├── README
│   ├── spi.c
│   └── tstoreReceiver.c
├── foreign
│   ├── foreign.c
│   └── Makefile
├── lib
│   ├── dllist.c
│   ├── Makefile
│   └── stringinfo.c
├── libpq
│   ├── auth.c
│   ├── be-fsstubs.c
│   ├── be-secure.c
│   ├── crypt.c
│   ├── hba.c
│   ├── ip.c
│   ├── Makefile
│   ├── md5.c
│   ├── pg_hba.conf.sample
│   ├── pg_ident.conf.sample
│   ├── pqcomm.c
│   ├── pqformat.c
│   ├── pqsignal.c
│   └── README.SSL
├── main
│   ├── main.c
│   └── Makefile
├── Makefile
├── nls.mk
├── nodes
│   ├── bitmapset.c
│   ├── copyfuncs.c
│   ├── equalfuncs.c
│   ├── list.c
│   ├── Makefile
│   ├── makefuncs.c
│   ├── nodeFuncs.c
│   ├── nodes.c
│   ├── outfuncs.c
│   ├── params.c
│   ├── print.c
│   ├── read.c
│   ├── readfuncs.c
│   ├── README
│   ├── tidbitmap.c
│   └── value.c
├── optimizer
│   ├── geqo
│   │   ├── geqo_copy.c
│   │   ├── geqo_cx.c
│   │   ├── geqo_erx.c
│   │   ├── geqo_eval.c
│   │   ├── geqo_main.c
│   │   ├── geqo_misc.c
│   │   ├── geqo_mutation.c
│   │   ├── geqo_ox1.c
│   │   ├── geqo_ox2.c
│   │   ├── geqo_pmx.c
│   │   ├── geqo_pool.c
│   │   ├── geqo_px.c
│   │   ├── geqo_recombination.c
│   │   ├── geqo_selection.c
│   │   └── Makefile
│   ├── Makefile
│   ├── path
│   │   ├── allpaths.c
│   │   ├── clausesel.c
│   │   ├── costsize.c
│   │   ├── equivclass.c
│   │   ├── indxpath.c
│   │   ├── joinpath.c
│   │   ├── joinrels.c
│   │   ├── Makefile
│   │   ├── orindxpath.c
│   │   ├── pathkeys.c
│   │   └── tidpath.c
│   ├── plan
│   │   ├── createplan.c
│   │   ├── initsplan.c
│   │   ├── Makefile
│   │   ├── planagg.c
│   │   ├── planmain.c
│   │   ├── planner.c
│   │   ├── README
│   │   ├── setrefs.c
│   │   └── subselect.c
│   ├── prep
│   │   ├── Makefile
│   │   ├── prepjointree.c
│   │   ├── prepqual.c
│   │   ├── preptlist.c
│   │   └── prepunion.c
│   ├── README
│   └── util
│       ├── clauses.c
│       ├── joininfo.c
│       ├── Makefile
│       ├── pathnode.c
│       ├── placeholder.c
│       ├── plancat.c
│       ├── predtest.c
│       ├── relnode.c
│       ├── restrictinfo.c
│       ├── tlist.c
│       └── var.c
├── parser
│   ├── analyze.c
│   ├── gram.y
│   ├── keywords.c
│   ├── kwlookup.c
│   ├── Makefile
│   ├── parse_agg.c
│   ├── parse_clause.c
│   ├── parse_coerce.c
│   ├── parse_cte.c
│   ├── parse_expr.c
│   ├── parse_func.c
│   ├── parse_node.c
│   ├── parse_oper.c
│   ├── parser.c
│   ├── parse_relation.c
│   ├── parse_target.c
│   ├── parse_type.c
│   ├── parse_utilcmd.c
│   ├── README
│   ├── scan.l
│   └── scansup.c
├── po
│   ├── de.po
│   ├── es.po
│   ├── fr.po
│   ├── ja.po
│   ├── pt_BR.po
│   └── tr.po
├── port
│   ├── aix
│   │   └── mkldexport.sh
│   ├── darwin
│   │   ├── Makefile
│   │   ├── README
│   │   └── system.c
│   ├── dynloader
│   │   ├── aix.c
│   │   ├── aix.h
│   │   ├── bsdi.c
│   │   ├── bsdi.h
│   │   ├── cygwin.c
│   │   ├── cygwin.h
│   │   ├── darwin.c
│   │   ├── darwin.h
│   │   ├── dgux.c
│   │   ├── dgux.h
│   │   ├── freebsd.c
│   │   ├── freebsd.h
│   │   ├── hpux.c
│   │   ├── hpux.h
│   │   ├── irix.c
│   │   ├── irix.h
│   │   ├── linux.c
│   │   ├── linux.h
│   │   ├── netbsd.c
│   │   ├── netbsd.h
│   │   ├── nextstep.c
│   │   ├── nextstep.h
│   │   ├── openbsd.c
│   │   ├── openbsd.h
│   │   ├── osf.c
│   │   ├── osf.h
│   │   ├── sco.c
│   │   ├── sco.h
│   │   ├── solaris.c
│   │   ├── solaris.h
│   │   ├── sunos4.c
│   │   ├── sunos4.h
│   │   ├── svr4.c
│   │   ├── svr4.h
│   │   ├── ultrix4.c
│   │   ├── ultrix4.h
│   │   ├── univel.c
│   │   ├── univel.h
│   │   ├── unixware.c
│   │   ├── unixware.h
│   │   ├── win32.c
│   │   └── win32.h
│   ├── hpux
│   │   └── tas.c.template
│   ├── ipc_test.c
│   ├── Makefile
│   ├── nextstep
│   │   ├── Makefile
│   │   └── port.c
│   ├── posix_sema.c
│   ├── sysv_sema.c
│   ├── sysv_shmem.c
│   ├── tas
│   │   ├── dummy.s
│   │   ├── hpux_hppa.s
│   │   ├── sunstudio_sparc.s
│   │   └── sunstudio_x86.s
│   ├── win32
│   │   ├── Makefile
│   │   ├── mingwcompat.c
│   │   ├── security.c
│   │   ├── signal.c
│   │   ├── socket.c
│   │   └── timer.c
│   ├── win32_sema.c
│   └── win32_shmem.c
├── postmaster
│   ├── autovacuum.c
│   ├── bgwriter.c
│   ├── fork_process.c
│   ├── Makefile
│   ├── pgarch.c
│   ├── pgstat.c
│   ├── postmaster.c
│   ├── syslogger.c
│   └── walwriter.c
├── readcode.md
├── regex
│   ├── COPYRIGHT
│   ├── Makefile
│   ├── regc_color.c
│   ├── regc_cvec.c
│   ├── regc_lex.c
│   ├── regc_locale.c
│   ├── regc_nfa.c
│   ├── regcomp.c
│   ├── rege_dfa.c
│   ├── regerror.c
│   ├── regexec.c
│   ├── regfree.c
│   └── re_syntax.n
├── rewrite
│   ├── Makefile
│   ├── rewriteDefine.c
│   ├── rewriteHandler.c
│   ├── rewriteManip.c
│   ├── rewriteRemove.c
│   └── rewriteSupport.c
├── snowball
│   ├── dict_snowball.c
│   ├── libstemmer
│   │   ├── api.c
│   │   ├── stem_ISO_8859_1_danish.c
│   │   ├── stem_ISO_8859_1_dutch.c
│   │   ├── stem_ISO_8859_1_english.c
│   │   ├── stem_ISO_8859_1_finnish.c
│   │   ├── stem_ISO_8859_1_french.c
│   │   ├── stem_ISO_8859_1_german.c
│   │   ├── stem_ISO_8859_1_hungarian.c
│   │   ├── stem_ISO_8859_1_italian.c
│   │   ├── stem_ISO_8859_1_norwegian.c
│   │   ├── stem_ISO_8859_1_porter.c
│   │   ├── stem_ISO_8859_1_portuguese.c
│   │   ├── stem_ISO_8859_1_spanish.c
│   │   ├── stem_ISO_8859_1_swedish.c
│   │   ├── stem_ISO_8859_2_romanian.c
│   │   ├── stem_KOI8_R_russian.c
│   │   ├── stem_UTF_8_danish.c
│   │   ├── stem_UTF_8_dutch.c
│   │   ├── stem_UTF_8_english.c
│   │   ├── stem_UTF_8_finnish.c
│   │   ├── stem_UTF_8_french.c
│   │   ├── stem_UTF_8_german.c
│   │   ├── stem_UTF_8_hungarian.c
│   │   ├── stem_UTF_8_italian.c
│   │   ├── stem_UTF_8_norwegian.c
│   │   ├── stem_UTF_8_porter.c
│   │   ├── stem_UTF_8_portuguese.c
│   │   ├── stem_UTF_8_romanian.c
│   │   ├── stem_UTF_8_russian.c
│   │   ├── stem_UTF_8_spanish.c
│   │   ├── stem_UTF_8_swedish.c
│   │   ├── stem_UTF_8_turkish.c
│   │   └── utilities.c
│   ├── Makefile
│   ├── README
│   ├── snowball_func.sql.in
│   ├── snowball.sql.in
│   └── stopwords
│       ├── danish.stop
│       ├── dutch.stop
│       ├── english.stop
│       ├── finnish.stop
│       ├── french.stop
│       ├── german.stop
│       ├── hungarian.stop
│       ├── italian.stop
│       ├── norwegian.stop
│       ├── portuguese.stop
│       ├── russian.stop
│       ├── spanish.stop
│       ├── swedish.stop
│       └── turkish.stop
├── storage
│   ├── buffer
│   │   ├── buf_init.c
│   │   ├── bufmgr.c
│   │   ├── buf_table.c
│   │   ├── freelist.c
│   │   ├── localbuf.c
│   │   ├── Makefile
│   │   └── README
│   ├── file
│   │   ├── buffile.c
│   │   ├── fd.c
│   │   └── Makefile
│   ├── freespace
│   │   ├── freespace.c
│   │   ├── fsmpage.c
│   │   ├── indexfsm.c
│   │   ├── Makefile
│   │   └── README
│   ├── ipc
│   │   ├── ipc.c
│   │   ├── ipci.c
│   │   ├── Makefile
│   │   ├── pmsignal.c
│   │   ├── procarray.c
│   │   ├── README
│   │   ├── shmem.c
│   │   ├── shmqueue.c
│   │   ├── sinvaladt.c
│   │   └── sinval.c
│   ├── large_object
│   │   ├── inv_api.c
│   │   └── Makefile
│   ├── lmgr
│   │   ├── deadlock.c
│   │   ├── lmgr.c
│   │   ├── lock.c
│   │   ├── lwlock.c
│   │   ├── Makefile
│   │   ├── proc.c
│   │   ├── README
│   │   ├── s_lock.c
│   │   └── spin.c
│   ├── Makefile
│   ├── page
│   │   ├── bufpage.c
│   │   ├── itemptr.c
│   │   └── Makefile
│   └── smgr
│       ├── Makefile
│       ├── md.c
│       ├── README
│       ├── smgr.c
│       └── smgrtype.c
├── tcop
│   ├── dest.c
│   ├── fastpath.c
│   ├── Makefile
│   ├── postgres.c
│   ├── pquery.c
│   └── utility.c
├── tsearch
│   ├── dict.c
│   ├── dict_ispell.c
│   ├── dict_simple.c
│   ├── dict_synonym.c
│   ├── dict_thesaurus.c
│   ├── hunspell_sample.affix
│   ├── ispell_sample.affix
│   ├── ispell_sample.dict
│   ├── Makefile
│   ├── regis.c
│   ├── spell.c
│   ├── synonym_sample.syn
│   ├── thesaurus_sample.ths
│   ├── to_tsany.c
│   ├── ts_locale.c
│   ├── ts_parse.c
│   ├── ts_selfuncs.c
│   ├── ts_typanalyze.c
│   ├── ts_utils.c
│   ├── wparser.c
│   └── wparser_def.c
└── utils
    ├── adt
    │   ├── acl.c
    │   ├── arrayfuncs.c
    │   ├── array_userfuncs.c
    │   ├── arrayutils.c
    │   ├── ascii.c
    │   ├── bool.c
    │   ├── cash.c
    │   ├── char.c
    │   ├── date.c
    │   ├── datetime.c
    │   ├── datum.c
    │   ├── dbsize.c
    │   ├── domains.c
    │   ├── encode.c
    │   ├── enum.c
    │   ├── float.c
    │   ├── formatting.c
    │   ├── format_type.c
    │   ├── genfile.c
    │   ├── geo_ops.c
    │   ├── geo_selfuncs.c
    │   ├── inet_net_ntop.c
    │   ├── inet_net_pton.c
    │   ├── int8.c
    │   ├── int.c
    │   ├── like.c
    │   ├── like_match.c
    │   ├── lockfuncs.c
    │   ├── mac.c
    │   ├── Makefile
    │   ├── misc.c
    │   ├── nabstime.c
    │   ├── name.c
    │   ├── network.c
    │   ├── numeric.c
    │   ├── numutils.c
    │   ├── oid.c
    │   ├── oracle_compat.c
    │   ├── pg_locale.c
    │   ├── pg_lzcompress.c
    │   ├── pgstatfuncs.c
    │   ├── pseudotypes.c
    │   ├── quote.c
    │   ├── regexp.c
    │   ├── regproc.c
    │   ├── ri_triggers.c
    │   ├── rowtypes.c
    │   ├── ruleutils.c
    │   ├── selfuncs.c
    │   ├── tid.c
    │   ├── timestamp.c
    │   ├── trigfuncs.c
    │   ├── tsginidx.c
    │   ├── tsgistidx.c
    │   ├── tsquery.c
    │   ├── tsquery_cleanup.c
    │   ├── tsquery_gist.c
    │   ├── tsquery_op.c
    │   ├── tsquery_rewrite.c
    │   ├── tsquery_util.c
    │   ├── tsrank.c
    │   ├── tsvector.c
    │   ├── tsvector_op.c
    │   ├── tsvector_parser.c
    │   ├── txid.c
    │   ├── uuid.c
    │   ├── varbit.c
    │   ├── varchar.c
    │   ├── varlena.c
    │   ├── version.c
    │   ├── windowfuncs.c
    │   ├── xid.c
    │   └── xml.c
    ├── cache
    │   ├── catcache.c
    │   ├── inval.c
    │   ├── lsyscache.c
    │   ├── Makefile
    │   ├── plancache.c
    │   ├── relcache.c
    │   ├── syscache.c
    │   ├── ts_cache.c
    │   └── typcache.c
    ├── error
    │   ├── assert.c
    │   ├── elog.c
    │   └── Makefile
    ├── fmgr
    │   ├── dfmgr.c
    │   ├── fmgr.c
    │   ├── funcapi.c
    │   ├── Makefile
    │   └── README
    ├── Gen_dummy_probes.sed
    ├── Gen_fmgrtab.pl
    ├── Gen_fmgrtab.sh
    ├── hash
    │   ├── dynahash.c
    │   ├── hashfn.c
    │   ├── Makefile
    │   └── pg_crc.c
    ├── init
    │   ├── flatfiles.c
    │   ├── globals.c
    │   ├── Makefile
    │   ├── miscinit.c
    │   └── postinit.c
    ├── Makefile
    ├── mb
    │   ├── conv.c
    │   ├── conversion_procs
    │   │   ├── ascii_and_mic
    │   │   │   ├── ascii_and_mic.c
    │   │   │   └── Makefile
    │   │   ├── cyrillic_and_mic
    │   │   │   ├── cyrillic_and_mic.c
    │   │   │   └── Makefile
    │   │   ├── euc_cn_and_mic
    │   │   │   ├── euc_cn_and_mic.c
    │   │   │   └── Makefile
    │   │   ├── euc_jis_2004_and_shift_jis_2004
    │   │   │   ├── euc_jis_2004_and_shift_jis_2004.c
    │   │   │   └── Makefile
    │   │   ├── euc_jp_and_sjis
    │   │   │   ├── euc_jp_and_sjis.c
    │   │   │   ├── Makefile
    │   │   │   └── sjis.map
    │   │   ├── euc_kr_and_mic
    │   │   │   ├── euc_kr_and_mic.c
    │   │   │   └── Makefile
    │   │   ├── euc_tw_and_big5
    │   │   │   ├── big5.c
    │   │   │   ├── euc_tw_and_big5.c
    │   │   │   └── Makefile
    │   │   ├── latin2_and_win1250
    │   │   │   ├── latin2_and_win1250.c
    │   │   │   └── Makefile
    │   │   ├── latin_and_mic
    │   │   │   ├── latin_and_mic.c
    │   │   │   └── Makefile
    │   │   ├── Makefile
    │   │   ├── proc.mk
    │   │   ├── README.euc_jp
    │   │   ├── regress_epilogue
    │   │   ├── regress_prolog
    │   │   ├── utf8_and_ascii
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_ascii.c
    │   │   ├── utf8_and_big5
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_big5.c
    │   │   ├── utf8_and_cyrillic
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_cyrillic.c
    │   │   ├── utf8_and_euc_cn
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_euc_cn.c
    │   │   ├── utf8_and_euc_jis_2004
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_euc_jis_2004.c
    │   │   ├── utf8_and_euc_jp
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_euc_jp.c
    │   │   ├── utf8_and_euc_kr
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_euc_kr.c
    │   │   ├── utf8_and_euc_tw
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_euc_tw.c
    │   │   ├── utf8_and_gb18030
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_gb18030.c
    │   │   ├── utf8_and_gbk
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_gbk.c
    │   │   ├── utf8_and_iso8859
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_iso8859.c
    │   │   ├── utf8_and_iso8859_1
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_iso8859_1.c
    │   │   ├── utf8_and_johab
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_johab.c
    │   │   ├── utf8_and_shift_jis_2004
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_shift_jis_2004.c
    │   │   ├── utf8_and_sjis
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_sjis.c
    │   │   ├── utf8_and_uhc
    │   │   │   ├── Makefile
    │   │   │   └── utf8_and_uhc.c
    │   │   └── utf8_and_win
    │   │       ├── Makefile
    │   │       └── utf8_and_win.c
    │   ├── encnames.c
    │   ├── iso.c
    │   ├── Makefile
    │   ├── mbutils.c
    │   ├── README
    │   ├── Unicode
    │   │   ├── big5_to_utf8.map
    │   │   ├── euc_cn_to_utf8.map
    │   │   ├── euc-jis-2004-std.txt
    │   │   ├── euc_jis_2004_to_utf8_combined.map
    │   │   ├── euc_jis_2004_to_utf8.map
    │   │   ├── euc_jp_to_utf8.map
    │   │   ├── euc_kr_to_utf8.map
    │   │   ├── euc_tw_to_utf8.map
    │   │   ├── gb18030_to_utf8.map
    │   │   ├── gbk_to_utf8.map
    │   │   ├── ISO10646-GB18030.TXT
    │   │   ├── iso8859_10_to_utf8.map
    │   │   ├── iso8859_13_to_utf8.map
    │   │   ├── iso8859_14_to_utf8.map
    │   │   ├── iso8859_15_to_utf8.map
    │   │   ├── iso8859_16_to_utf8.map
    │   │   ├── iso8859_2_to_utf8.map
    │   │   ├── iso8859_3_to_utf8.map
    │   │   ├── iso8859_4_to_utf8.map
    │   │   ├── iso8859_5_to_utf8.map
    │   │   ├── iso8859_6_to_utf8.map
    │   │   ├── iso8859_7_to_utf8.map
    │   │   ├── iso8859_8_to_utf8.map
    │   │   ├── iso8859_9_to_utf8.map
    │   │   ├── johab_to_utf8.map
    │   │   ├── koi8r_to_utf8.map
    │   │   ├── koi8u_to_utf8.map
    │   │   ├── Makefile
    │   │   ├── shift_jis_2004_to_utf8_combined.map
    │   │   ├── shift_jis_2004_to_utf8.map
    │   │   ├── sjis-0213-2004-std.txt
    │   │   ├── sjis_to_utf8.map
    │   │   ├── ucs2utf.pl
    │   │   ├── UCS_to_BIG5.pl
    │   │   ├── UCS_to_EUC_CN.pl
    │   │   ├── UCS_to_EUC_JIS_2004.pl
    │   │   ├── UCS_to_EUC_JP.pl
    │   │   ├── UCS_to_EUC_KR.pl
    │   │   ├── UCS_to_EUC_TW.pl
    │   │   ├── UCS_to_GB18030.pl
    │   │   ├── UCS_to_most.pl
    │   │   ├── UCS_to_SHIFT_JIS_2004.pl
    │   │   ├── UCS_to_SJIS.pl
    │   │   ├── uhc_to_utf8.map
    │   │   ├── utf8_to_big5.map
    │   │   ├── utf8_to_euc_cn.map
    │   │   ├── utf8_to_euc_jis_2004_combined.map
    │   │   ├── utf8_to_euc_jis_2004.map
    │   │   ├── utf8_to_euc_jp.map
    │   │   ├── utf8_to_euc_kr.map
    │   │   ├── utf8_to_euc_tw.map
    │   │   ├── utf8_to_gb18030.map
    │   │   ├── utf8_to_gbk.map
    │   │   ├── utf8_to_iso8859_10.map
    │   │   ├── utf8_to_iso8859_13.map
    │   │   ├── utf8_to_iso8859_14.map
    │   │   ├── utf8_to_iso8859_15.map
    │   │   ├── utf8_to_iso8859_16.map
    │   │   ├── utf8_to_iso8859_2.map
    │   │   ├── utf8_to_iso8859_3.map
    │   │   ├── utf8_to_iso8859_4.map
    │   │   ├── utf8_to_iso8859_5.map
    │   │   ├── utf8_to_iso8859_6.map
    │   │   ├── utf8_to_iso8859_7.map
    │   │   ├── utf8_to_iso8859_8.map
    │   │   ├── utf8_to_iso8859_9.map
    │   │   ├── utf8_to_johab.map
    │   │   ├── utf8_to_koi8r.map
    │   │   ├── utf8_to_koi8u.map
    │   │   ├── utf8_to_shift_jis_2004_combined.map
    │   │   ├── utf8_to_shift_jis_2004.map
    │   │   ├── utf8_to_sjis.map
    │   │   ├── utf8_to_uhc.map
    │   │   ├── utf8_to_win1250.map
    │   │   ├── utf8_to_win1251.map
    │   │   ├── utf8_to_win1252.map
    │   │   ├── utf8_to_win1253.map
    │   │   ├── utf8_to_win1254.map
    │   │   ├── utf8_to_win1255.map
    │   │   ├── utf8_to_win1256.map
    │   │   ├── utf8_to_win1257.map
    │   │   ├── utf8_to_win1258.map
    │   │   ├── utf8_to_win866.map
    │   │   ├── utf8_to_win874.map
    │   │   ├── win1250_to_utf8.map
    │   │   ├── win1251_to_utf8.map
    │   │   ├── win1252_to_utf8.map
    │   │   ├── win1253_to_utf8.map
    │   │   ├── win1254_to_utf8.map
    │   │   ├── win1255_to_utf8.map
    │   │   ├── win1256_to_utf8.map
    │   │   ├── win1257_to_utf8.map
    │   │   ├── win1258_to_utf8.map
    │   │   ├── win866_to_utf8.map
    │   │   └── win874_to_utf8.map
    │   ├── wchar.c
    │   ├── win1251.c
    │   ├── win866.c
    │   ├── wstrcmp.c
    │   └── wstrncmp.c
    ├── misc
    │   ├── check_guc
    │   ├── guc.c
    │   ├── guc-file.l
    │   ├── help_config.c
    │   ├── Makefile
    │   ├── pg_rusage.c
    │   ├── postgresql.conf.sample
    │   ├── ps_status.c
    │   ├── README
    │   ├── superuser.c
    │   └── tzparser.c
    ├── mmgr
    │   ├── aset.c
    │   ├── Makefile
    │   ├── mcxt.c
    │   ├── portalmem.c
    │   └── README
    ├── probes.d
    ├── resowner
    │   ├── Makefile
    │   ├── README
    │   └── resowner.c
    ├── sort
    │   ├── logtape.c
    │   ├── Makefile
    │   ├── tuplesort.c
    │   └── tuplestore.c
    └── time
        ├── combocid.c
        ├── Makefile
        ├── snapmgr.c
        └── tqual.c

92 directories, 825 files
