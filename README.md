# Server Metrics 2026-03-13 08:41:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 96192.5 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2702668
telemt_connections_bad_total 36282
telemt_handshake_timeouts_total 33797
telemt_upstream_connect_attempt_total 18712
telemt_upstream_connect_success_total 18610
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 18712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 22721
telemt_me_reconnect_success_total 13846
telemt_me_reader_eof_total 14913
telemt_me_idle_close_by_peer_total 14912
telemt_me_route_drop_no_conn_total 1005470
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2470503
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11079
telemt_desync_full_logged_total 2866
telemt_desync_suppressed_total 8213
telemt_desync_frames_bucket_total{bucket="1_2"} 2847
telemt_desync_frames_bucket_total{bucket="3_10"} 4145
telemt_desync_frames_bucket_total{bucket="gt_10"} 4087
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14317
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13833
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 2470075
telemt_user_connections_current{user="hello"} 1613
telemt_user_octets_from_client{user="hello"} 34720792792 (32.34 GB)
telemt_user_octets_to_client{user="hello"} 819555175088 (763.27 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 125813.2 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1100350
telemt_connections_bad_total 13729
telemt_handshake_timeouts_total 89589
telemt_upstream_connect_attempt_total 31340
telemt_upstream_connect_success_total 31309
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23549
telemt_me_reconnect_success_total 23428
telemt_me_reader_eof_total 24969
telemt_me_idle_close_by_peer_total 24969
telemt_me_route_drop_no_conn_total 339024
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955734
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4213
telemt_desync_full_logged_total 1285
telemt_desync_suppressed_total 2928
telemt_desync_frames_bucket_total{bucket="1_2"} 1554
telemt_desync_frames_bucket_total{bucket="3_10"} 1382
telemt_desync_frames_bucket_total{bucket="gt_10"} 1277
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 23658
telemt_me_writer_restored_same_endpoint_total 23419
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 957663
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 14669660332 (13.66 GB)
telemt_user_octets_to_client{user="hello"} 355001236275 (330.62 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 125813.2 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2146515
telemt_connections_bad_total 23676
telemt_handshake_timeouts_total 143577
telemt_upstream_connect_attempt_total 28858
telemt_upstream_connect_success_total 28848
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1750
telemt_me_reconnect_attempts_total 23535
telemt_me_reconnect_success_total 22253
telemt_me_reader_eof_total 23573
telemt_me_idle_close_by_peer_total 23572
telemt_me_route_drop_no_conn_total 696186
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1711710
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5747
telemt_desync_full_logged_total 1816
telemt_desync_suppressed_total 3931
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 2100
telemt_desync_frames_bucket_total{bucket="gt_10"} 2704
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22469
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22212
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 1711163
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 29885207440 (27.83 GB)
telemt_user_octets_to_client{user="hello"} 620899995425 (578.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 125813.6 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1364717
telemt_connections_bad_total 14221
telemt_handshake_timeouts_total 83880
telemt_upstream_connect_attempt_total 41907
telemt_upstream_connect_success_total 39606
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41633
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11450
telemt_me_reconnect_attempts_total 36439
telemt_me_reconnect_success_total 27499
telemt_me_reader_eof_total 29613
telemt_me_idle_close_by_peer_total 29606
telemt_me_route_drop_no_conn_total 478733
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1135313
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2192
telemt_desync_full_logged_total 715
telemt_desync_suppressed_total 1477
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 843
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27971
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27475
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 1140075
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 17185217481 (16.00 GB)
telemt_user_octets_to_client{user="hello"} 454522713010 (423.31 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 125813.4 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1508040
telemt_connections_bad_total 31203
telemt_handshake_timeouts_total 12455
telemt_upstream_connect_attempt_total 39800
telemt_upstream_connect_success_total 39321
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 39800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_keepalive_timeout_total 2146
telemt_me_reconnect_attempts_total 46819
telemt_me_reconnect_success_total 33076
telemt_me_reader_eof_total 34686
telemt_me_idle_close_by_peer_total 34686
telemt_me_seq_mismatch_total 46
telemt_me_route_drop_no_conn_total 552375
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1381462
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 50
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4836
telemt_desync_full_logged_total 1731
telemt_desync_suppressed_total 3105
telemt_desync_frames_bucket_total{bucket="1_2"} 1475
telemt_desync_frames_bucket_total{bucket="3_10"} 1558
telemt_desync_frames_bucket_total{bucket="gt_10"} 1803
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33868
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 33018
telemt_me_writer_restored_fallback_total 58
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 792
telemt_user_connections_total{user="hello"} 1381264
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 17994545884 (16.76 GB)
telemt_user_octets_to_client{user="hello"} 479937111168 (446.98 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 105
```