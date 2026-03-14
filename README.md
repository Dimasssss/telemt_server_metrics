# Server Metrics 2026-03-14 01:17:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 155956.6 (43h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4628735
telemt_connections_bad_total 39794
telemt_handshake_timeouts_total 108049
telemt_upstream_connect_attempt_total 32987
telemt_upstream_connect_success_total 32767
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 32987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 6673
telemt_me_reconnect_attempts_total 32781
telemt_me_reconnect_success_total 22647
telemt_me_reader_eof_total 24287
telemt_me_idle_close_by_peer_total 24286
telemt_me_route_drop_no_conn_total 1752713
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4242824
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16687
telemt_desync_full_logged_total 4499
telemt_desync_suppressed_total 12188
telemt_desync_frames_bucket_total{bucket="1_2"} 4161
telemt_desync_frames_bucket_total{bucket="3_10"} 6375
telemt_desync_frames_bucket_total{bucket="gt_10"} 6151
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 23287
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22634
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 4244681
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 62566886588 (58.27 GB)
telemt_user_octets_to_client{user="hello"} 1341984236013 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55620.1 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673056
telemt_connections_bad_total 50458
telemt_handshake_timeouts_total 12936
telemt_upstream_connect_attempt_total 15538
telemt_upstream_connect_success_total 15290
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 15538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 2024
telemt_me_reconnect_attempts_total 13928
telemt_me_reconnect_success_total 10485
telemt_me_reader_eof_total 11121
telemt_me_idle_close_by_peer_total 11120
telemt_me_route_drop_no_conn_total 229483
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544774
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1650
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10740
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10477
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 546725
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 5910163717 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 176977125756 (164.82 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 185576.8 (51h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3351124
telemt_connections_bad_total 34317
telemt_handshake_timeouts_total 222653
telemt_upstream_connect_attempt_total 41663
telemt_upstream_connect_success_total 41642
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10363
telemt_me_reconnect_attempts_total 37031
telemt_me_reconnect_success_total 32073
telemt_me_reader_eof_total 34054
telemt_me_idle_close_by_peer_total 34053
telemt_me_route_drop_no_conn_total 1150030
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2786391
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9169
telemt_desync_full_logged_total 3080
telemt_desync_suppressed_total 6089
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 3319
telemt_desync_frames_bucket_total{bucket="gt_10"} 4305
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 32529
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32032
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 2785629
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 44968413804 (41.88 GB)
telemt_user_octets_to_client{user="hello"} 992878507809 (924.69 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 185579.5 (51h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2230486
telemt_connections_bad_total 22924
telemt_handshake_timeouts_total 241101
telemt_upstream_connect_attempt_total 57949
telemt_upstream_connect_success_total 55490
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 57675
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20389
telemt_me_reconnect_attempts_total 48241
telemt_me_reconnect_success_total 39213
telemt_me_reader_eof_total 42060
telemt_me_idle_close_by_peer_total 42053
telemt_me_route_drop_no_conn_total 767424
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1788072
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3801
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 39836
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39189
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 1793990
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 27414670499 (25.53 GB)
telemt_user_octets_to_client{user="hello"} 664135149662 (618.52 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55013.2 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682830
telemt_connections_bad_total 7886
telemt_handshake_timeouts_total 8619
telemt_upstream_connect_attempt_total 13697
telemt_upstream_connect_success_total 13312
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 13697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_keepalive_timeout_total 1473
telemt_me_reconnect_attempts_total 42691
telemt_me_reconnect_success_total 10534
telemt_me_reader_eof_total 11766
telemt_me_idle_close_by_peer_total 11765
telemt_me_route_drop_no_conn_total 258761
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 635329
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1126
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11629
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10529
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1095
telemt_user_connections_total{user="hello"} 635228
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 10566950536 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 207840336716 (193.57 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 20
```