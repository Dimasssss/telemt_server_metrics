# Server Metrics 2026-03-15 18:30:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 72965.2 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2619868
telemt_connections_bad_total 151926
telemt_handshake_timeouts_total 34957
telemt_upstream_connect_attempt_total 14052
telemt_upstream_connect_success_total 13991
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 14052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15239
telemt_me_reconnect_success_total 10340
telemt_me_reader_eof_total 11054
telemt_me_idle_close_by_peer_total 11054
telemt_me_route_drop_no_conn_total 908673
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2188948
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8460
telemt_desync_full_logged_total 2317
telemt_desync_suppressed_total 6143
telemt_desync_frames_bucket_total{bucket="1_2"} 2084
telemt_desync_frames_bucket_total{bucket="3_10"} 3229
telemt_desync_frames_bucket_total{bucket="gt_10"} 3147
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10669
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10329
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 2188414
telemt_user_connections_current{user="hello"} 2254
telemt_user_octets_from_client{user="hello"} 33149486796 (30.87 GB)
telemt_user_octets_to_client{user="hello"} 834624551800 (777.30 GB)
telemt_user_unique_ips_current{user="hello"} 661
telemt_user_unique_ips_recent_window{user="hello"} 325
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 72966.1 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014616
telemt_connections_bad_total 58564
telemt_handshake_timeouts_total 64295
telemt_upstream_connect_attempt_total 18018
telemt_upstream_connect_success_total 17919
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 18017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 15117
telemt_me_reconnect_success_total 13904
telemt_me_reader_eof_total 14713
telemt_me_idle_close_by_peer_total 14713
telemt_me_route_drop_no_conn_total 263278
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784825
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2253
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 1483
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14124
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13892
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 785054
telemt_user_connections_current{user="hello"} 840
telemt_user_octets_from_client{user="hello"} 11347039311 (10.57 GB)
telemt_user_octets_to_client{user="hello"} 294853713004 (274.60 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 72966.0 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2213830
telemt_connections_bad_total 51215
telemt_handshake_timeouts_total 215820
telemt_upstream_connect_attempt_total 15628
telemt_upstream_connect_success_total 15549
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 15628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 13134
telemt_me_reconnect_success_total 11864
telemt_me_reader_eof_total 12571
telemt_me_idle_close_by_peer_total 12571
telemt_me_route_drop_no_conn_total 577856
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1393607
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3664
telemt_desync_full_logged_total 1317
telemt_desync_suppressed_total 2347
telemt_desync_frames_bucket_total{bucket="1_2"} 837
telemt_desync_frames_bucket_total{bucket="3_10"} 1434
telemt_desync_frames_bucket_total{bucket="gt_10"} 1393
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12073
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11845
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 1389480
telemt_user_connections_current{user="hello"} 1421
telemt_user_octets_from_client{user="hello"} 25777143328 (24.01 GB)
telemt_user_octets_to_client{user="hello"} 523982128104 (488.00 GB)
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 72966.0 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1078609
telemt_connections_bad_total 82091
telemt_handshake_timeouts_total 52826
telemt_upstream_connect_attempt_total 171057
telemt_upstream_connect_success_total 170452
telemt_upstream_connect_fail_total 605
telemt_upstream_connect_attempts_per_request{bucket="1"} 171057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 605
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61896
telemt_me_reconnect_success_total 13830
telemt_me_reader_eof_total 15706
telemt_me_idle_close_by_peer_total 15706
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 257458
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688912
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1931
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1394
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 745
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15476
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13794
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 841423
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 15471277765 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 300377966764 (279.75 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 72966.8 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1094445
telemt_connections_bad_total 12684
telemt_handshake_timeouts_total 23574
telemt_upstream_connect_attempt_total 15951
telemt_upstream_connect_success_total 15866
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 15951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15898
telemt_me_reconnect_success_total 12203
telemt_me_reader_eof_total 13017
telemt_me_idle_close_by_peer_total 13017
telemt_me_route_drop_no_conn_total 277058
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3182
telemt_desync_full_logged_total 1049
telemt_desync_suppressed_total 2133
telemt_desync_frames_bucket_total{bucket="1_2"} 958
telemt_desync_frames_bucket_total{bucket="3_10"} 1169
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12466
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 12195
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 908626
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 11257264936 (10.48 GB)
telemt_user_octets_to_client{user="hello"} 318242459820 (296.39 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 121
```