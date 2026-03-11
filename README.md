# Server Metrics 2026-03-11 14:05:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 85106.6 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2034572
telemt_connections_bad_total 29144
telemt_handshake_timeouts_total 51937
telemt_upstream_connect_attempt_total 17850
telemt_upstream_connect_success_total 17840
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 17850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3191
telemt_me_reconnect_attempts_total 26374
telemt_me_reconnect_success_total 13538
telemt_me_reader_eof_total 14596
telemt_me_idle_close_by_peer_total 14596
telemt_me_route_drop_no_conn_total 749255
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1860142
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9768
telemt_desync_full_logged_total 2649
telemt_desync_suppressed_total 7119
telemt_desync_frames_bucket_total{bucket="1_2"} 2416
telemt_desync_frames_bucket_total{bucket="3_10"} 3776
telemt_desync_frames_bucket_total{bucket="gt_10"} 3576
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14087
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13532
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 1858648
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 24952320568 (23.24 GB)
telemt_user_octets_to_client{user="hello"} 528695443160 (492.39 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85163.3 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766446
telemt_connections_bad_total 13107
telemt_handshake_timeouts_total 51833
telemt_upstream_connect_attempt_total 27373
telemt_upstream_connect_success_total 24424
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2511
telemt_me_reconnect_attempts_total 19289
telemt_me_reconnect_success_total 17206
telemt_me_reader_eof_total 18213
telemt_me_idle_close_by_peer_total 18210
telemt_me_route_drop_no_conn_total 299732
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648453
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2812
telemt_desync_full_logged_total 891
telemt_desync_suppressed_total 1921
telemt_desync_frames_bucket_total{bucket="1_2"} 874
telemt_desync_frames_bucket_total{bucket="3_10"} 1023
telemt_desync_frames_bucket_total{bucket="gt_10"} 915
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17458
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17183
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 650940
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 6929726862 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 184082449152 (171.44 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 85163.2 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1325829
telemt_connections_bad_total 8360
telemt_handshake_timeouts_total 120841
telemt_upstream_connect_attempt_total 22670
telemt_upstream_connect_success_total 22399
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 22670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 903
telemt_me_reconnect_attempts_total 33143
telemt_me_reconnect_success_total 17033
telemt_me_reader_eof_total 18304
telemt_me_idle_close_by_peer_total 18304
telemt_me_route_drop_no_conn_total 477978
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1147460
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3046
telemt_desync_full_logged_total 903
telemt_desync_suppressed_total 2143
telemt_desync_frames_bucket_total{bucket="1_2"} 729
telemt_desync_frames_bucket_total{bucket="3_10"} 1153
telemt_desync_frames_bucket_total{bucket="gt_10"} 1164
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17762
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17022
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 1147263
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 13820409181 (12.87 GB)
telemt_user_octets_to_client{user="hello"} 342419736437 (318.90 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 85163.8 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 951687
telemt_connections_bad_total 77271
telemt_handshake_timeouts_total 89917
telemt_upstream_connect_attempt_total 23120
telemt_upstream_connect_success_total 23120
telemt_upstream_connect_attempts_per_request{bucket="1"} 23120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 951
telemt_me_reconnect_attempts_total 19938
telemt_me_reconnect_success_total 18867
telemt_me_reader_eof_total 20009
telemt_me_idle_close_by_peer_total 20008
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 308216
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758627
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1609
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 979
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 19099
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18839
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 757977
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 8740596584 (8.14 GB)
telemt_user_octets_to_client{user="hello"} 219850017372 (204.75 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85163.3 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1043755
telemt_connections_bad_total 6826
telemt_handshake_timeouts_total 9484
telemt_upstream_connect_attempt_total 23076
telemt_upstream_connect_success_total 22976
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 23076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 983
telemt_me_reconnect_attempts_total 22669
telemt_me_reconnect_success_total 18595
telemt_me_reader_eof_total 19625
telemt_me_idle_close_by_peer_total 19625
telemt_me_route_drop_no_conn_total 370055
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 948222
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3755
telemt_desync_full_logged_total 1385
telemt_desync_suppressed_total 2370
telemt_desync_frames_bucket_total{bucket="1_2"} 1318
telemt_desync_frames_bucket_total{bucket="3_10"} 1414
telemt_desync_frames_bucket_total{bucket="gt_10"} 1023
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18961
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18595
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 947959
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 13777458843 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 335327821430 (312.30 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 103
```