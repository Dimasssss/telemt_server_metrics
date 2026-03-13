# Server Metrics 2026-03-13 13:53:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 114915.1 (31h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3488394
telemt_connections_bad_total 37389
telemt_handshake_timeouts_total 59656
telemt_upstream_connect_attempt_total 22518
telemt_upstream_connect_success_total 22394
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 2131
telemt_me_reconnect_attempts_total 26766
telemt_me_reconnect_success_total 16682
telemt_me_reader_eof_total 17934
telemt_me_idle_close_by_peer_total 17933
telemt_me_route_drop_no_conn_total 1294055
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3201950
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13283
telemt_desync_full_logged_total 3472
telemt_desync_suppressed_total 9811
telemt_desync_frames_bucket_total{bucket="1_2"} 3383
telemt_desync_frames_bucket_total{bucket="3_10"} 5027
telemt_desync_frames_bucket_total{bucket="gt_10"} 4873
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17229
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16669
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 3201821
telemt_user_connections_current{user="hello"} 1668
telemt_user_octets_from_client{user="hello"} 44213195380 (41.18 GB)
telemt_user_octets_to_client{user="hello"} 1018304254252 (948.37 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14578.9 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202977
telemt_connections_bad_total 11591
telemt_handshake_timeouts_total 5243
telemt_upstream_connect_attempt_total 3528
telemt_upstream_connect_success_total 3451
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 3528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 3888
telemt_me_reconnect_success_total 2657
telemt_me_reader_eof_total 2787
telemt_me_idle_close_by_peer_total 2787
telemt_me_route_drop_no_conn_total 73792
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180847
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 713
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 548
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2718
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2650
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 180872
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 1812323828 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 50617131092 (47.14 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 144535.7 (40h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2618019
telemt_connections_bad_total 26848
telemt_handshake_timeouts_total 175146
telemt_upstream_connect_attempt_total 32671
telemt_upstream_connect_success_total 32661
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3207
telemt_me_reconnect_attempts_total 27674
telemt_me_reconnect_success_total 25128
telemt_me_reader_eof_total 26641
telemt_me_idle_close_by_peer_total 26640
telemt_me_route_drop_no_conn_total 879046
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2135681
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7450
telemt_desync_full_logged_total 2439
telemt_desync_suppressed_total 5011
telemt_desync_frames_bucket_total{bucket="1_2"} 1180
telemt_desync_frames_bucket_total{bucket="3_10"} 2709
telemt_desync_frames_bucket_total{bucket="gt_10"} 3561
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 25420
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25087
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 2135102
telemt_user_connections_current{user="hello"} 1149
telemt_user_octets_from_client{user="hello"} 35637500440 (33.19 GB)
telemt_user_octets_to_client{user="hello"} 760993406621 (708.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 144536.2 (40h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1668697
telemt_connections_bad_total 18055
telemt_handshake_timeouts_total 118333
telemt_upstream_connect_attempt_total 46090
telemt_upstream_connect_success_total 43768
telemt_upstream_connect_fail_total 2185
telemt_upstream_connect_attempts_per_request{bucket="1"} 45816
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11839
telemt_me_reconnect_attempts_total 39688
telemt_me_reconnect_success_total 30721
telemt_me_reader_eof_total 33032
telemt_me_idle_close_by_peer_total 33025
telemt_me_route_drop_no_conn_total 595436
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1396143
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2811
telemt_desync_full_logged_total 911
telemt_desync_suppressed_total 1900
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 1170
telemt_desync_frames_bucket_total{bucket="gt_10"} 892
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 31231
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30697
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 1400870
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 21579003865 (20.10 GB)
telemt_user_octets_to_client{user="hello"} 542794203914 (505.52 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13971.5 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219469
telemt_connections_bad_total 3857
telemt_handshake_timeouts_total 1955
telemt_upstream_connect_attempt_total 2885
telemt_upstream_connect_success_total 2786
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 2885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 10122
telemt_me_reconnect_success_total 2046
telemt_me_reader_eof_total 2312
telemt_me_idle_close_by_peer_total 2312
telemt_me_route_drop_no_conn_total 86111
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205203
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 725
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 497
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2300
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2042
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 205186
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 2113229384 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 61861772616 (57.61 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 96
```