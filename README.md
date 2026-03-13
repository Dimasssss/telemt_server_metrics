# Server Metrics 2026-03-13 16:52:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 125639.3 (34h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3986356
telemt_connections_bad_total 37514
telemt_handshake_timeouts_total 99861
telemt_upstream_connect_attempt_total 24361
telemt_upstream_connect_success_total 24222
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 2299
telemt_me_reconnect_attempts_total 28073
telemt_me_reconnect_success_total 17975
telemt_me_reader_eof_total 19314
telemt_me_idle_close_by_peer_total 19313
telemt_me_route_drop_no_conn_total 1479488
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3641049
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14351
telemt_desync_full_logged_total 3789
telemt_desync_suppressed_total 10562
telemt_desync_frames_bucket_total{bucket="1_2"} 3581
telemt_desync_frames_bucket_total{bucket="3_10"} 5435
telemt_desync_frames_bucket_total{bucket="gt_10"} 5335
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18538
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17962
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 3640852
telemt_user_connections_current{user="hello"} 1643
telemt_user_octets_from_client{user="hello"} 51360942908 (47.83 GB)
telemt_user_octets_to_client{user="hello"} 1136668914796 (1.03 TB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25303.2 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373844
telemt_connections_bad_total 26936
telemt_handshake_timeouts_total 10148
telemt_upstream_connect_attempt_total 6011
telemt_upstream_connect_success_total 5923
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 6011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 7942
telemt_me_reconnect_success_total 4589
telemt_me_reader_eof_total 4874
telemt_me_idle_close_by_peer_total 4873
telemt_me_route_drop_no_conn_total 134364
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327556
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1148
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 848
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4755
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4582
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 327590
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 3279861432 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 95090170092 (88.56 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 155259.9 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2924052
telemt_connections_bad_total 28312
telemt_handshake_timeouts_total 196156
telemt_upstream_connect_attempt_total 34718
telemt_upstream_connect_success_total 34708
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3346
telemt_me_reconnect_attempts_total 29199
telemt_me_reconnect_success_total 26645
telemt_me_reader_eof_total 28255
telemt_me_idle_close_by_peer_total 28254
telemt_me_route_drop_no_conn_total 993014
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2409707
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8413
telemt_desync_full_logged_total 2779
telemt_desync_suppressed_total 5634
telemt_desync_frames_bucket_total{bucket="1_2"} 1355
telemt_desync_frames_bucket_total{bucket="3_10"} 3077
telemt_desync_frames_bucket_total{bucket="gt_10"} 3981
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 26957
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26604
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 2409074
telemt_user_connections_current{user="hello"} 1113
telemt_user_octets_from_client{user="hello"} 39260145968 (36.56 GB)
telemt_user_octets_to_client{user="hello"} 840306779929 (782.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 155260.3 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1884118
telemt_connections_bad_total 18183
telemt_handshake_timeouts_total 172081
telemt_upstream_connect_attempt_total 48564
telemt_upstream_connect_success_total 46228
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 48290
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11923
telemt_me_reconnect_attempts_total 41624
telemt_me_reconnect_success_total 32645
telemt_me_reader_eof_total 35063
telemt_me_idle_close_by_peer_total 35056
telemt_me_route_drop_no_conn_total 669356
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1552831
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3087
telemt_desync_full_logged_total 1004
telemt_desync_suppressed_total 2083
telemt_desync_frames_bucket_total{bucket="1_2"} 846
telemt_desync_frames_bucket_total{bucket="3_10"} 1275
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 33181
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32621
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 1557528
telemt_user_connections_current{user="hello"} 813
telemt_user_octets_from_client{user="hello"} 24104268937 (22.45 GB)
telemt_user_octets_to_client{user="hello"} 591549599094 (550.92 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24695.9 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401974
telemt_connections_bad_total 4211
telemt_handshake_timeouts_total 3821
telemt_upstream_connect_attempt_total 5608
telemt_upstream_connect_success_total 5447
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 5608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 15875
telemt_me_reconnect_success_total 4178
telemt_me_reader_eof_total 4641
telemt_me_idle_close_by_peer_total 4641
telemt_me_route_drop_no_conn_total 156236
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375617
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1225
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 839
telemt_desync_frames_bucket_total{bucket="1_2"} 407
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4574
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4174
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 375592
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 4340756112 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 119304739628 (111.11 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 97
```