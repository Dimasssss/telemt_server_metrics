# Server Metrics 2026-03-13 08:46:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 96498.6 (26h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2716833
telemt_connections_bad_total 36282
telemt_handshake_timeouts_total 35567
telemt_upstream_connect_attempt_total 18835
telemt_upstream_connect_success_total 18731
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 18835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 1368
telemt_me_reconnect_attempts_total 22798
telemt_me_reconnect_success_total 13922
telemt_me_reader_eof_total 14990
telemt_me_idle_close_by_peer_total 14989
telemt_me_route_drop_no_conn_total 1009653
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2482940
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11144
telemt_desync_full_logged_total 2877
telemt_desync_suppressed_total 8267
telemt_desync_frames_bucket_total{bucket="1_2"} 2859
telemt_desync_frames_bucket_total{bucket="3_10"} 4171
telemt_desync_frames_bucket_total{bucket="gt_10"} 4114
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14394
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13909
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 2482509
telemt_user_connections_current{user="hello"} 1719
telemt_user_octets_from_client{user="hello"} 34882187600 (32.49 GB)
telemt_user_octets_to_client{user="hello"} 821983554808 (765.53 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 126119.1 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107674
telemt_connections_bad_total 13777
telemt_handshake_timeouts_total 93656
telemt_upstream_connect_attempt_total 31423
telemt_upstream_connect_success_total 31392
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23589
telemt_me_reconnect_success_total 23467
telemt_me_reader_eof_total 25009
telemt_me_idle_close_by_peer_total 25009
telemt_me_route_drop_no_conn_total 340326
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959317
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4237
telemt_desync_full_logged_total 1291
telemt_desync_suppressed_total 2946
telemt_desync_frames_bucket_total{bucket="1_2"} 1557
telemt_desync_frames_bucket_total{bucket="3_10"} 1395
telemt_desync_frames_bucket_total{bucket="gt_10"} 1285
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 23697
telemt_me_writer_restored_same_endpoint_total 23458
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 961246
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 14696982328 (13.69 GB)
telemt_user_octets_to_client{user="hello"} 355857837239 (331.42 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 126119.0 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2153260
telemt_connections_bad_total 23679
telemt_handshake_timeouts_total 143917
telemt_upstream_connect_attempt_total 28918
telemt_upstream_connect_success_total 28908
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1761
telemt_me_reconnect_attempts_total 23567
telemt_me_reconnect_success_total 22285
telemt_me_reader_eof_total 23605
telemt_me_idle_close_by_peer_total 23604
telemt_me_route_drop_no_conn_total 698476
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1718008
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5759
telemt_desync_full_logged_total 1823
telemt_desync_suppressed_total 3936
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 2104
telemt_desync_frames_bucket_total{bucket="gt_10"} 2712
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22501
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22244
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 1717453
telemt_user_connections_current{user="hello"} 997
telemt_user_octets_from_client{user="hello"} 29967466744 (27.91 GB)
telemt_user_octets_to_client{user="hello"} 622947547025 (580.17 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 126119.3 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1368681
telemt_connections_bad_total 14222
telemt_handshake_timeouts_total 84247
telemt_upstream_connect_attempt_total 41974
telemt_upstream_connect_success_total 39673
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41700
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11450
telemt_me_reconnect_attempts_total 36463
telemt_me_reconnect_success_total 27523
telemt_me_reader_eof_total 29638
telemt_me_idle_close_by_peer_total 29631
telemt_me_route_drop_no_conn_total 480221
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1138791
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2193
telemt_desync_full_logged_total 716
telemt_desync_suppressed_total 1477
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 843
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 27996
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27499
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 1143556
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 17224913169 (16.04 GB)
telemt_user_octets_to_client{user="hello"} 455495337110 (424.21 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 126119.1 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1513733
telemt_connections_bad_total 31674
telemt_handshake_timeouts_total 12483
telemt_upstream_connect_attempt_total 39951
telemt_upstream_connect_success_total 39466
telemt_upstream_connect_fail_total 484
telemt_upstream_connect_attempts_per_request{bucket="1"} 39950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 484
telemt_me_keepalive_timeout_total 2149
telemt_me_reconnect_attempts_total 46923
telemt_me_reconnect_success_total 33179
telemt_me_reader_eof_total 34789
telemt_me_idle_close_by_peer_total 34789
telemt_me_seq_mismatch_total 47
telemt_me_route_drop_no_conn_total 554027
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1386095
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 51
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4859
telemt_desync_full_logged_total 1737
telemt_desync_suppressed_total 3122
telemt_desync_frames_bucket_total{bucket="1_2"} 1483
telemt_desync_frames_bucket_total{bucket="3_10"} 1566
telemt_desync_frames_bucket_total{bucket="gt_10"} 1810
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33972
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 33120
telemt_me_writer_restored_fallback_total 59
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 793
telemt_user_connections_total{user="hello"} 1385895
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 18026747008 (16.79 GB)
telemt_user_octets_to_client{user="hello"} 481881508508 (448.79 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 90
```