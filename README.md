# Server Metrics 2026-03-13 07:15:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 90985.8 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2482893
telemt_connections_bad_total 36153
telemt_handshake_timeouts_total 26216
telemt_upstream_connect_attempt_total 17771
telemt_upstream_connect_success_total 17672
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 1349
telemt_me_reconnect_attempts_total 22006
telemt_me_reconnect_success_total 13135
telemt_me_reader_eof_total 14164
telemt_me_idle_close_by_peer_total 14163
telemt_me_route_drop_no_conn_total 935221
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2279253
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10177
telemt_desync_full_logged_total 2629
telemt_desync_suppressed_total 7548
telemt_desync_frames_bucket_total{bucket="1_2"} 2601
telemt_desync_frames_bucket_total{bucket="3_10"} 3745
telemt_desync_frames_bucket_total{bucket="gt_10"} 3831
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 13597
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13122
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 2278781
telemt_user_connections_current{user="hello"} 1507
telemt_user_octets_from_client{user="hello"} 32795105308 (30.54 GB)
telemt_user_octets_to_client{user="hello"} 770787526588 (717.85 GB)
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 120606.2 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 993242
telemt_connections_bad_total 12718
telemt_handshake_timeouts_total 46388
telemt_upstream_connect_attempt_total 30308
telemt_upstream_connect_success_total 30277
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3605
telemt_me_reconnect_attempts_total 22781
telemt_me_reconnect_success_total 22661
telemt_me_reader_eof_total 24146
telemt_me_idle_close_by_peer_total 24146
telemt_me_route_drop_no_conn_total 315885
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 894188
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3857
telemt_desync_full_logged_total 1185
telemt_desync_suppressed_total 2672
telemt_desync_frames_bucket_total{bucket="1_2"} 1476
telemt_desync_frames_bucket_total{bucket="3_10"} 1243
telemt_desync_frames_bucket_total{bucket="gt_10"} 1138
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22883
telemt_me_writer_restored_same_endpoint_total 22652
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 896113
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 13868997692 (12.92 GB)
telemt_user_octets_to_client{user="hello"} 338241182267 (315.01 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 120606.1 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2034434
telemt_connections_bad_total 23358
telemt_handshake_timeouts_total 136393
telemt_upstream_connect_attempt_total 27786
telemt_upstream_connect_success_total 27776
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1707
telemt_me_reconnect_attempts_total 22722
telemt_me_reconnect_success_total 21446
telemt_me_reader_eof_total 22716
telemt_me_idle_close_by_peer_total 22715
telemt_me_route_drop_no_conn_total 652743
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1609172
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5496
telemt_desync_full_logged_total 1703
telemt_desync_suppressed_total 3793
telemt_desync_frames_bucket_total{bucket="1_2"} 900
telemt_desync_frames_bucket_total{bucket="3_10"} 1998
telemt_desync_frames_bucket_total{bucket="gt_10"} 2598
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21654
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21405
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 1608660
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 27058005048 (25.20 GB)
telemt_user_octets_to_client{user="hello"} 579886042973 (540.06 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 120606.6 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1245575
telemt_connections_bad_total 14060
telemt_handshake_timeouts_total 80666
telemt_upstream_connect_attempt_total 40736
telemt_upstream_connect_success_total 38440
telemt_upstream_connect_fail_total 2159
telemt_upstream_connect_attempts_per_request{bucket="1"} 40462
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2158
telemt_me_keepalive_timeout_total 11430
telemt_me_reconnect_attempts_total 35535
telemt_me_reconnect_success_total 26598
telemt_me_reader_eof_total 28647
telemt_me_idle_close_by_peer_total 28640
telemt_me_route_drop_no_conn_total 450157
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1070750
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2102
telemt_desync_full_logged_total 682
telemt_desync_suppressed_total 1420
telemt_desync_frames_bucket_total{bucket="1_2"} 579
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 713
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 27059
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26574
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 1075504
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 16418771137 (15.29 GB)
telemt_user_octets_to_client{user="hello"} 425788636682 (396.55 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 120606.3 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1406922
telemt_connections_bad_total 23174
telemt_handshake_timeouts_total 11594
telemt_upstream_connect_attempt_total 38305
telemt_upstream_connect_success_total 37840
telemt_upstream_connect_fail_total 465
telemt_upstream_connect_attempts_per_request{bucket="1"} 38305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18431
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 465
telemt_me_keepalive_timeout_total 2089
telemt_me_reconnect_attempts_total 45603
telemt_me_reconnect_success_total 31865
telemt_me_reader_eof_total 33421
telemt_me_idle_close_by_peer_total 33421
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 516642
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1295150
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4646
telemt_desync_full_logged_total 1654
telemt_desync_suppressed_total 2992
telemt_desync_frames_bucket_total{bucket="1_2"} 1404
telemt_desync_frames_bucket_total{bucket="3_10"} 1501
telemt_desync_frames_bucket_total{bucket="gt_10"} 1741
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 32640
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31809
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 775
telemt_user_connections_total{user="hello"} 1294988
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 16485006848 (15.35 GB)
telemt_user_octets_to_client{user="hello"} 444092232704 (413.59 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 99
```