# Server Metrics 2026-03-11 12:48:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 80509.9 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1872767
telemt_connections_bad_total 27757
telemt_handshake_timeouts_total 48271
telemt_upstream_connect_attempt_total 16690
telemt_upstream_connect_success_total 16681
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 874
telemt_me_reconnect_attempts_total 25434
telemt_me_reconnect_success_total 12606
telemt_me_reader_eof_total 13631
telemt_me_idle_close_by_peer_total 13631
telemt_me_route_drop_no_conn_total 689142
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1708103
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8902
telemt_desync_full_logged_total 2406
telemt_desync_suppressed_total 6496
telemt_desync_frames_bucket_total{bucket="1_2"} 2206
telemt_desync_frames_bucket_total{bucket="3_10"} 3421
telemt_desync_frames_bucket_total{bucket="gt_10"} 3275
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13143
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12600
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 1706643
telemt_user_connections_current{user="hello"} 1483
telemt_user_octets_from_client{user="hello"} 22627830124 (21.07 GB)
telemt_user_octets_to_client{user="hello"} 484671123604 (451.39 GB)
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 80566.6 (22h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712442
telemt_connections_bad_total 13027
telemt_handshake_timeouts_total 50269
telemt_upstream_connect_attempt_total 26119
telemt_upstream_connect_success_total 23177
telemt_upstream_connect_fail_total 2942
telemt_upstream_connect_attempts_per_request{bucket="1"} 26119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2942
telemt_me_keepalive_timeout_total 2431
telemt_me_reconnect_attempts_total 17048
telemt_me_reconnect_success_total 16187
telemt_me_reader_eof_total 17131
telemt_me_idle_close_by_peer_total 17128
telemt_me_route_drop_no_conn_total 280180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598705
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2677
telemt_desync_full_logged_total 845
telemt_desync_suppressed_total 1832
telemt_desync_frames_bucket_total{bucket="1_2"} 846
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 858
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 16395
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16164
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 600991
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 6470834806 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 172552036716 (160.70 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 80566.5 (22h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1225831
telemt_connections_bad_total 8108
telemt_handshake_timeouts_total 114852
telemt_upstream_connect_attempt_total 21620
telemt_upstream_connect_success_total 21358
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 21620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 874
telemt_me_reconnect_attempts_total 30980
telemt_me_reconnect_success_total 16225
telemt_me_reader_eof_total 17425
telemt_me_idle_close_by_peer_total 17425
telemt_me_route_drop_no_conn_total 421620
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1056647
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2853
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 2003
telemt_desync_frames_bucket_total{bucket="1_2"} 693
telemt_desync_frames_bucket_total{bucket="3_10"} 1072
telemt_desync_frames_bucket_total{bucket="gt_10"} 1088
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16899
telemt_me_refill_failed_total 457
telemt_me_writer_restored_same_endpoint_total 16214
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 674
telemt_user_connections_total{user="hello"} 1057088
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 12372029449 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 317125753889 (295.35 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 80567.1 (22h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 885111
telemt_connections_bad_total 75691
telemt_handshake_timeouts_total 82007
telemt_upstream_connect_attempt_total 21942
telemt_upstream_connect_success_total 21942
telemt_upstream_connect_attempts_per_request{bucket="1"} 21942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 870
telemt_me_reconnect_attempts_total 18980
telemt_me_reconnect_success_total 17914
telemt_me_reader_eof_total 19002
telemt_me_idle_close_by_peer_total 19001
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 283699
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 702770
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1472
telemt_desync_full_logged_total 574
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 530
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 411
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18134
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17887
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 702129
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 7979311612 (7.43 GB)
telemt_user_octets_to_client{user="hello"} 201143770332 (187.33 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80566.5 (22h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958019
telemt_connections_bad_total 6806
telemt_handshake_timeouts_total 8940
telemt_upstream_connect_attempt_total 22016
telemt_upstream_connect_success_total 21921
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 22016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 930
telemt_me_reconnect_attempts_total 21836
telemt_me_reconnect_success_total 17769
telemt_me_reader_eof_total 18753
telemt_me_idle_close_by_peer_total 18753
telemt_me_route_drop_no_conn_total 337473
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 870053
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3531
telemt_desync_full_logged_total 1303
telemt_desync_suppressed_total 2228
telemt_desync_frames_bucket_total{bucket="1_2"} 1219
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 952
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18124
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17769
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 869806
telemt_user_connections_current{user="hello"} 892
telemt_user_octets_from_client{user="hello"} 12819918975 (11.94 GB)
telemt_user_octets_to_client{user="hello"} 313512320726 (291.98 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 115
```