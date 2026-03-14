# Server Metrics 2026-03-14 06:04:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 173134.0 (48h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4878531
telemt_connections_bad_total 40027
telemt_handshake_timeouts_total 112556
telemt_upstream_connect_attempt_total 36416
telemt_upstream_connect_success_total 36179
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 36416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 7311
telemt_me_reconnect_attempts_total 35372
telemt_me_reconnect_success_total 25225
telemt_me_reader_eof_total 27075
telemt_me_idle_close_by_peer_total 27074
telemt_me_route_drop_no_conn_total 1847938
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4476786
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17199
telemt_desync_full_logged_total 4643
telemt_desync_suppressed_total 12556
telemt_desync_frames_bucket_total{bucket="1_2"} 4296
telemt_desync_frames_bucket_total{bucket="3_10"} 6570
telemt_desync_frames_bucket_total{bucket="gt_10"} 6333
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 25904
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25212
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 679
telemt_user_connections_total{user="hello"} 4478320
telemt_user_connections_current{user="hello"} 1159
telemt_user_octets_from_client{user="hello"} 65390872376 (60.90 GB)
telemt_user_octets_to_client{user="hello"} 1412098519157 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72797.9 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793312
telemt_connections_bad_total 53200
telemt_handshake_timeouts_total 14602
telemt_upstream_connect_attempt_total 19830
telemt_upstream_connect_success_total 19560
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 19830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 2120
telemt_me_reconnect_attempts_total 17379
telemt_me_reconnect_success_total 13919
telemt_me_reader_eof_total 14795
telemt_me_idle_close_by_peer_total 14794
telemt_me_route_drop_no_conn_total 258688
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627421
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1857
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14219
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13911
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 629373
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 6657593789 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 211957320756 (197.40 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 202754.6 (56h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3504994
telemt_connections_bad_total 38307
telemt_handshake_timeouts_total 231233
telemt_upstream_connect_attempt_total 45866
telemt_upstream_connect_success_total 45845
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10632
telemt_me_reconnect_attempts_total 40409
telemt_me_reconnect_success_total 35437
telemt_me_reader_eof_total 37641
telemt_me_idle_close_by_peer_total 37640
telemt_me_route_drop_no_conn_total 1198684
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2922404
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9662
telemt_desync_full_logged_total 3243
telemt_desync_suppressed_total 6419
telemt_desync_frames_bucket_total{bucket="1_2"} 1685
telemt_desync_frames_bucket_total{bucket="3_10"} 3490
telemt_desync_frames_bucket_total{bucket="gt_10"} 4487
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 35929
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35396
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 2921565
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 47761490432 (44.48 GB)
telemt_user_octets_to_client{user="hello"} 1045543683497 (973.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 202757.2 (56h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2344765
telemt_connections_bad_total 23179
telemt_handshake_timeouts_total 271802
telemt_upstream_connect_attempt_total 63293
telemt_upstream_connect_success_total 60808
telemt_upstream_connect_fail_total 2348
telemt_upstream_connect_attempts_per_request{bucket="1"} 63019
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2347
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20483
telemt_me_reconnect_attempts_total 52732
telemt_me_reconnect_success_total 43690
telemt_me_reader_eof_total 46848
telemt_me_idle_close_by_peer_total 46841
telemt_me_route_drop_no_conn_total 792685
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1854255
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3889
telemt_desync_full_logged_total 1256
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1047
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 180
telemt_me_writer_removed_unexpected_total 44350
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43666
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1860262
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 28140287611 (26.21 GB)
telemt_user_octets_to_client{user="hello"} 683286702774 (636.36 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72190.8 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768896
telemt_connections_bad_total 8031
telemt_handshake_timeouts_total 9053
telemt_upstream_connect_attempt_total 18594
telemt_upstream_connect_success_total 18096
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 18594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 1563
telemt_me_reconnect_attempts_total 58055
telemt_me_reconnect_success_total 14478
telemt_me_reader_eof_total 16195
telemt_me_idle_close_by_peer_total 16194
telemt_me_route_drop_no_conn_total 295410
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718182
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1758
telemt_desync_full_logged_total 560
telemt_desync_suppressed_total 1198
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 550
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15965
telemt_me_refill_failed_total 1357
telemt_me_writer_restored_same_endpoint_total 14473
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1487
telemt_user_connections_total{user="hello"} 718043
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 12801022804 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 239718730196 (223.26 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 67
```