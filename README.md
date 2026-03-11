# Server Metrics 2026-03-11 19:47:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 105630.7 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2681261
telemt_connections_bad_total 48666
telemt_handshake_timeouts_total 59604
telemt_upstream_connect_attempt_total 22309
telemt_upstream_connect_success_total 22297
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5395
telemt_me_reconnect_attempts_total 34827
telemt_me_reconnect_success_total 16934
telemt_me_reader_eof_total 18292
telemt_me_idle_close_by_peer_total 18292
telemt_me_route_drop_no_conn_total 1012925
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2449623
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12403
telemt_desync_full_logged_total 3438
telemt_desync_suppressed_total 8965
telemt_desync_frames_bucket_total{bucket="1_2"} 3047
telemt_desync_frames_bucket_total{bucket="3_10"} 4786
telemt_desync_frames_bucket_total{bucket="gt_10"} 4570
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17685
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16928
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 2447974
telemt_user_connections_current{user="hello"} 1118
telemt_user_octets_from_client{user="hello"} 36529348920 (34.02 GB)
telemt_user_octets_to_client{user="hello"} 695252678944 (647.50 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 105687.3 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 996107
telemt_connections_bad_total 16481
telemt_handshake_timeouts_total 89952
telemt_upstream_connect_attempt_total 32523
telemt_upstream_connect_success_total 29551
telemt_upstream_connect_fail_total 2972
telemt_upstream_connect_attempts_per_request{bucket="1"} 32523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2972
telemt_me_keepalive_timeout_total 2860
telemt_me_reconnect_attempts_total 23396
telemt_me_reconnect_success_total 21275
telemt_me_reader_eof_total 22528
telemt_me_idle_close_by_peer_total 22525
telemt_me_route_drop_no_conn_total 376421
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 831006
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3314
telemt_desync_full_logged_total 1072
telemt_desync_suppressed_total 2242
telemt_desync_frames_bucket_total{bucket="1_2"} 1055
telemt_desync_frames_bucket_total{bucket="3_10"} 1180
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21585
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21252
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 833457
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 10020832194 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 242176816172 (225.54 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 105687.3 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1718726
telemt_connections_bad_total 10660
telemt_handshake_timeouts_total 134382
telemt_upstream_connect_attempt_total 27141
telemt_upstream_connect_success_total 26801
telemt_upstream_connect_fail_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 27141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 340
telemt_me_keepalive_timeout_total 2009
telemt_me_reconnect_attempts_total 54089
telemt_me_reconnect_success_total 20370
telemt_me_reader_eof_total 22281
telemt_me_idle_close_by_peer_total 22281
telemt_me_route_drop_no_conn_total 626051
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1509070
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4124
telemt_desync_full_logged_total 1214
telemt_desync_suppressed_total 2910
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 1568
telemt_desync_frames_bucket_total{bucket="gt_10"} 1594
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21703
telemt_me_refill_failed_total 1048
telemt_me_writer_restored_same_endpoint_total 20358
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1333
telemt_user_connections_total{user="hello"} 1508713
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 19404474353 (18.07 GB)
telemt_user_octets_to_client{user="hello"} 460483178077 (428.86 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 105687.8 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1227686
telemt_connections_bad_total 78218
telemt_handshake_timeouts_total 110961
telemt_upstream_connect_attempt_total 28550
telemt_upstream_connect_success_total 28550
telemt_upstream_connect_attempts_per_request{bucket="1"} 28550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1471
telemt_me_reconnect_attempts_total 27869
telemt_me_reconnect_success_total 23254
telemt_me_reader_eof_total 24690
telemt_me_idle_close_by_peer_total 24689
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 410544
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003155
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2140
telemt_desync_full_logged_total 805
telemt_desync_suppressed_total 1335
telemt_desync_frames_bucket_total{bucket="1_2"} 766
telemt_desync_frames_bucket_total{bucket="3_10"} 725
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23639
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23221
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 1002367
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 11924142920 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 307361419812 (286.25 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10363.7 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163807
telemt_connections_bad_total 2782
telemt_handshake_timeouts_total 1304
telemt_upstream_connect_attempt_total 3013
telemt_upstream_connect_success_total 3012
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2457
telemt_me_reconnect_success_total 2432
telemt_me_reader_eof_total 2504
telemt_me_idle_close_by_peer_total 2504
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 54654
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145372
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 326
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2459
telemt_me_writer_restored_same_endpoint_total 2407
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 145338
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 9324041484 (8.68 GB)
telemt_user_octets_to_client{user="hello"} 48765270920 (45.42 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 62
```