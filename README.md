# Server Metrics 2026-03-11 17:50:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 98589.3 (27h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2492282
telemt_connections_bad_total 46749
telemt_handshake_timeouts_total 55522
telemt_upstream_connect_attempt_total 20741
telemt_upstream_connect_success_total 20729
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5238
telemt_me_reconnect_attempts_total 33615
telemt_me_reconnect_success_total 15736
telemt_me_reader_eof_total 17037
telemt_me_idle_close_by_peer_total 17037
telemt_me_route_drop_no_conn_total 927093
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2279886
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11738
telemt_desync_full_logged_total 3224
telemt_desync_suppressed_total 8514
telemt_desync_frames_bucket_total{bucket="1_2"} 2894
telemt_desync_frames_bucket_total{bucket="3_10"} 4537
telemt_desync_frames_bucket_total{bucket="gt_10"} 4307
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16472
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15730
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 736
telemt_user_connections_total{user="hello"} 2278328
telemt_user_connections_current{user="hello"} 1269
telemt_user_octets_from_client{user="hello"} 31058072860 (28.93 GB)
telemt_user_octets_to_client{user="hello"} 644480598340 (600.22 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98645.7 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 936990
telemt_connections_bad_total 16343
telemt_handshake_timeouts_total 83090
telemt_upstream_connect_attempt_total 30913
telemt_upstream_connect_success_total 27949
telemt_upstream_connect_fail_total 2964
telemt_upstream_connect_attempts_per_request{bucket="1"} 30913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2964
telemt_me_keepalive_timeout_total 2762
telemt_me_reconnect_attempts_total 22146
telemt_me_reconnect_success_total 20038
telemt_me_reader_eof_total 21206
telemt_me_idle_close_by_peer_total 21203
telemt_me_route_drop_no_conn_total 354195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780485
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3082
telemt_desync_full_logged_total 984
telemt_desync_suppressed_total 2098
telemt_desync_frames_bucket_total{bucket="1_2"} 940
telemt_desync_frames_bucket_total{bucket="3_10"} 1104
telemt_desync_frames_bucket_total{bucket="gt_10"} 1038
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20317
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20015
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 782946
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 9456593406 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 221264216356 (206.07 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 98645.8 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1598909
telemt_connections_bad_total 9646
telemt_handshake_timeouts_total 129084
telemt_upstream_connect_attempt_total 25569
telemt_upstream_connect_success_total 25247
telemt_upstream_connect_fail_total 322
telemt_upstream_connect_attempts_per_request{bucket="1"} 25569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 322
telemt_me_keepalive_timeout_total 1896
telemt_me_reconnect_attempts_total 45193
telemt_me_reconnect_success_total 19189
telemt_me_reader_eof_total 20846
telemt_me_idle_close_by_peer_total 20846
telemt_me_route_drop_no_conn_total 582488
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1398672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3769
telemt_desync_full_logged_total 1097
telemt_desync_suppressed_total 2672
telemt_desync_frames_bucket_total{bucket="1_2"} 904
telemt_desync_frames_bucket_total{bucket="3_10"} 1435
telemt_desync_frames_bucket_total{bucket="gt_10"} 1430
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20265
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19177
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1076
telemt_user_connections_total{user="hello"} 1398358
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 17287181973 (16.10 GB)
telemt_user_octets_to_client{user="hello"} 425718475737 (396.48 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 98646.2 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1142887
telemt_connections_bad_total 77991
telemt_handshake_timeouts_total 107434
telemt_upstream_connect_attempt_total 26653
telemt_upstream_connect_success_total 26653
telemt_upstream_connect_attempts_per_request{bucket="1"} 26653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1262
telemt_me_reconnect_attempts_total 25076
telemt_me_reconnect_success_total 21720
telemt_me_reader_eof_total 23043
telemt_me_idle_close_by_peer_total 23042
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 378495
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 923689
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1933
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1191
telemt_desync_frames_bucket_total{bucket="1_2"} 687
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 571
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 22056
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 21687
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 922966
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 11085671876 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 281113505864 (261.81 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3322.1 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59617
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 358
telemt_upstream_connect_attempt_total 1032
telemt_upstream_connect_success_total 1032
telemt_upstream_connect_attempts_per_request{bucket="1"} 1032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 830
telemt_me_reconnect_success_total 823
telemt_me_reader_eof_total 803
telemt_me_idle_close_by_peer_total 803
telemt_me_route_drop_no_conn_total 19906
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56059
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 122
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_me_writer_removed_unexpected_total 826
telemt_me_writer_restored_same_endpoint_total 801
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 56056
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 5837046552 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 20913632528 (19.48 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 94
```