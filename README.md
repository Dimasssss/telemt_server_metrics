# Server Metrics 2026-03-11 19:37:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 105018.9 (29h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2666906
telemt_connections_bad_total 48659
telemt_handshake_timeouts_total 58896
telemt_upstream_connect_attempt_total 22127
telemt_upstream_connect_success_total 22115
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5346
telemt_me_reconnect_attempts_total 34691
telemt_me_reconnect_success_total 16798
telemt_me_reader_eof_total 18156
telemt_me_idle_close_by_peer_total 18156
telemt_me_route_drop_no_conn_total 1007586
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2437017
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12337
telemt_desync_full_logged_total 3424
telemt_desync_suppressed_total 8913
telemt_desync_frames_bucket_total{bucket="1_2"} 3024
telemt_desync_frames_bucket_total{bucket="3_10"} 4767
telemt_desync_frames_bucket_total{bucket="gt_10"} 4546
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17549
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16792
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 2435368
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 36389034416 (33.89 GB)
telemt_user_octets_to_client{user="hello"} 690816981756 (643.37 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 105075.6 (29h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 991782
telemt_connections_bad_total 16474
telemt_handshake_timeouts_total 89471
telemt_upstream_connect_attempt_total 32344
telemt_upstream_connect_success_total 29373
telemt_upstream_connect_fail_total 2971
telemt_upstream_connect_attempts_per_request{bucket="1"} 32344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2061
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2971
telemt_me_keepalive_timeout_total 2855
telemt_me_reconnect_attempts_total 23262
telemt_me_reconnect_success_total 21144
telemt_me_reader_eof_total 22393
telemt_me_idle_close_by_peer_total 22390
telemt_me_route_drop_no_conn_total 374881
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 827365
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3296
telemt_desync_full_logged_total 1067
telemt_desync_suppressed_total 2229
telemt_desync_frames_bucket_total{bucket="1_2"} 1049
telemt_desync_frames_bucket_total{bucket="3_10"} 1171
telemt_desync_frames_bucket_total{bucket="gt_10"} 1076
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21448
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21121
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 829811
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 9957013198 (9.27 GB)
telemt_user_octets_to_client{user="hello"} 240749691396 (224.22 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 105075.6 (29h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1710384
telemt_connections_bad_total 10660
telemt_handshake_timeouts_total 134251
telemt_upstream_connect_attempt_total 27035
telemt_upstream_connect_success_total 26696
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 27035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 1989
telemt_me_reconnect_attempts_total 52689
telemt_me_reconnect_success_total 20314
telemt_me_reader_eof_total 22184
telemt_me_idle_close_by_peer_total 22184
telemt_me_route_drop_no_conn_total 622995
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1500980
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4113
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 2901
telemt_desync_frames_bucket_total{bucket="1_2"} 961
telemt_desync_frames_bucket_total{bucket="3_10"} 1560
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21605
telemt_me_refill_failed_total 1006
telemt_me_writer_restored_same_endpoint_total 20302
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1291
telemt_user_connections_total{user="hello"} 1500633
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 19330779457 (18.00 GB)
telemt_user_octets_to_client{user="hello"} 457644469037 (426.21 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 105076.1 (29h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1222059
telemt_connections_bad_total 78201
telemt_handshake_timeouts_total 110797
telemt_upstream_connect_attempt_total 28372
telemt_upstream_connect_success_total 28372
telemt_upstream_connect_attempts_per_request{bucket="1"} 28372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1440
telemt_me_reconnect_attempts_total 27735
telemt_me_reconnect_success_total 23120
telemt_me_reader_eof_total 24544
telemt_me_idle_close_by_peer_total 24543
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 408493
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 997851
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2139
telemt_desync_full_logged_total 804
telemt_desync_suppressed_total 1335
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 725
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 23505
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23087
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 997064
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 11878039208 (11.06 GB)
telemt_user_octets_to_client{user="hello"} 304184850112 (283.29 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9751.8 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153880
telemt_connections_bad_total 1774
telemt_handshake_timeouts_total 1168
telemt_upstream_connect_attempt_total 2855
telemt_upstream_connect_success_total 2854
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2343
telemt_me_reconnect_success_total 2322
telemt_me_reader_eof_total 2385
telemt_me_idle_close_by_peer_total 2385
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 52415
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139112
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 294
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2349
telemt_me_writer_restored_same_endpoint_total 2297
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 139078
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 9262506992 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 47366642788 (44.11 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 78
```