# Server Metrics 2026-03-13 15:51:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 121966.9 (33h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3815094
telemt_connections_bad_total 37431
telemt_handshake_timeouts_total 84911
telemt_upstream_connect_attempt_total 23722
telemt_upstream_connect_success_total 23587
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2197
telemt_me_reconnect_attempts_total 27615
telemt_me_reconnect_success_total 17525
telemt_me_reader_eof_total 18835
telemt_me_idle_close_by_peer_total 18834
telemt_me_route_drop_no_conn_total 1414668
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3490814
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14029
telemt_desync_full_logged_total 3709
telemt_desync_suppressed_total 10320
telemt_desync_frames_bucket_total{bucket="1_2"} 3515
telemt_desync_frames_bucket_total{bucket="3_10"} 5305
telemt_desync_frames_bucket_total{bucket="gt_10"} 5209
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 18079
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17512
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3490615
telemt_user_connections_current{user="hello"} 1471
telemt_user_octets_from_client{user="hello"} 47482914616 (44.22 GB)
telemt_user_octets_to_client{user="hello"} 1095586377680 (1020.34 GB)
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21630.9 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312055
telemt_connections_bad_total 16784
telemt_handshake_timeouts_total 8653
telemt_upstream_connect_attempt_total 5014
telemt_upstream_connect_success_total 4928
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 5014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 6112
telemt_me_reconnect_success_total 3821
telemt_me_reader_eof_total 4060
telemt_me_idle_close_by_peer_total 4060
telemt_me_route_drop_no_conn_total 112590
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278610
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1050
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 780
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 507
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3942
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3814
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 278638
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 2801814340 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 79445197592 (73.99 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 151587.5 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2819441
telemt_connections_bad_total 27805
telemt_handshake_timeouts_total 187685
telemt_upstream_connect_attempt_total 34005
telemt_upstream_connect_success_total 33995
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3284
telemt_me_reconnect_attempts_total 28663
telemt_me_reconnect_success_total 26113
telemt_me_reader_eof_total 27695
telemt_me_idle_close_by_peer_total 27694
telemt_me_route_drop_no_conn_total 952984
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2316857
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8212
telemt_desync_full_logged_total 2718
telemt_desync_suppressed_total 5494
telemt_desync_frames_bucket_total{bucket="1_2"} 1315
telemt_desync_frames_bucket_total{bucket="3_10"} 2982
telemt_desync_frames_bucket_total{bucket="gt_10"} 3915
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 26421
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26072
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 2316253
telemt_user_connections_current{user="hello"} 1059
telemt_user_octets_from_client{user="hello"} 38206209036 (35.58 GB)
telemt_user_octets_to_client{user="hello"} 810156471101 (754.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 151587.8 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1795127
telemt_connections_bad_total 18149
telemt_handshake_timeouts_total 141033
telemt_upstream_connect_attempt_total 47752
telemt_upstream_connect_success_total 45420
telemt_upstream_connect_fail_total 2195
telemt_upstream_connect_attempts_per_request{bucket="1"} 47478
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2194
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11884
telemt_me_reconnect_attempts_total 40990
telemt_me_reconnect_success_total 32017
telemt_me_reader_eof_total 34398
telemt_me_idle_close_by_peer_total 34391
telemt_me_route_drop_no_conn_total 643804
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1496131
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3003
telemt_desync_full_logged_total 972
telemt_desync_suppressed_total 2031
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 1241
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 32543
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31993
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 1500840
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 23301649161 (21.70 GB)
telemt_user_octets_to_client{user="hello"} 574428178150 (534.98 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21024.1 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338358
telemt_connections_bad_total 4028
telemt_handshake_timeouts_total 3083
telemt_upstream_connect_attempt_total 4580
telemt_upstream_connect_success_total 4443
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 13926
telemt_me_reconnect_success_total 3352
telemt_me_reader_eof_total 3750
telemt_me_idle_close_by_peer_total 3750
telemt_me_route_drop_no_conn_total 133950
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317118
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1056
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 723
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 419
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3701
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3348
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 317093
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 3700850868 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 102059886044 (95.05 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 89
```