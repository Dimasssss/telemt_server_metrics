# Server Metrics 2026-03-13 15:10:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 119501.3 (33h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3704620
telemt_connections_bad_total 37420
telemt_handshake_timeouts_total 74674
telemt_upstream_connect_attempt_total 23285
telemt_upstream_connect_success_total 23153
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 23285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 2184
telemt_me_reconnect_attempts_total 27310
telemt_me_reconnect_success_total 17223
telemt_me_reader_eof_total 18511
telemt_me_idle_close_by_peer_total 18510
telemt_me_route_drop_no_conn_total 1374940
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3394170
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13870
telemt_desync_full_logged_total 3657
telemt_desync_suppressed_total 10213
telemt_desync_frames_bucket_total{bucket="1_2"} 3491
telemt_desync_frames_bucket_total{bucket="3_10"} 5261
telemt_desync_frames_bucket_total{bucket="gt_10"} 5118
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 17777
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17210
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3393938
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 46387690184 (43.20 GB)
telemt_user_octets_to_client{user="hello"} 1070174576292 (996.68 GB)
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19165.4 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274169
telemt_connections_bad_total 14528
telemt_handshake_timeouts_total 7151
telemt_upstream_connect_attempt_total 4615
telemt_upstream_connect_success_total 4530
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 5805
telemt_me_reconnect_success_total 3514
telemt_me_reader_eof_total 3731
telemt_me_idle_close_by_peer_total 3731
telemt_me_route_drop_no_conn_total 99544
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245391
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 937
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 700
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3625
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3507
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 245416
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 2492428480 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 69367640424 (64.60 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 149121.8 (41h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2747068
telemt_connections_bad_total 27409
telemt_handshake_timeouts_total 182886
telemt_upstream_connect_attempt_total 33533
telemt_upstream_connect_success_total 33523
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16009
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3264
telemt_me_reconnect_attempts_total 28321
telemt_me_reconnect_success_total 25773
telemt_me_reader_eof_total 27330
telemt_me_idle_close_by_peer_total 27329
telemt_me_route_drop_no_conn_total 927084
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2252409
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8022
telemt_desync_full_logged_total 2638
telemt_desync_suppressed_total 5384
telemt_desync_frames_bucket_total{bucket="1_2"} 1269
telemt_desync_frames_bucket_total{bucket="3_10"} 2926
telemt_desync_frames_bucket_total{bucket="gt_10"} 3827
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 26072
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25732
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 2251779
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 37296272876 (34.73 GB)
telemt_user_octets_to_client{user="hello"} 792354517121 (737.94 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 149122.2 (41h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1750060
telemt_connections_bad_total 18127
telemt_handshake_timeouts_total 132313
telemt_upstream_connect_attempt_total 47049
telemt_upstream_connect_success_total 44720
telemt_upstream_connect_fail_total 2192
telemt_upstream_connect_attempts_per_request{bucket="1"} 46775
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2191
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11864
telemt_me_reconnect_attempts_total 40422
telemt_me_reconnect_success_total 31451
telemt_me_reader_eof_total 33796
telemt_me_idle_close_by_peer_total 33789
telemt_me_route_drop_no_conn_total 627010
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1461231
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2942
telemt_desync_full_logged_total 952
telemt_desync_suppressed_total 1990
telemt_desync_frames_bucket_total{bucket="1_2"} 784
telemt_desync_frames_bucket_total{bucket="3_10"} 1223
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 31969
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31427
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 1465943
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 22885814005 (21.31 GB)
telemt_user_octets_to_client{user="hello"} 560654171122 (522.15 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18557.9 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296925
telemt_connections_bad_total 3956
telemt_handshake_timeouts_total 2753
telemt_upstream_connect_attempt_total 3995
telemt_upstream_connect_success_total 3868
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 3995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 13482
telemt_me_reconnect_success_total 2908
telemt_me_reader_eof_total 3274
telemt_me_idle_close_by_peer_total 3274
telemt_me_route_drop_no_conn_total 117871
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277868
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 849
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 578
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3251
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 2904
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 277847
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 3214754772 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 89138266564 (83.02 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 116
```