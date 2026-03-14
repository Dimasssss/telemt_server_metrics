# Server Metrics 2026-03-14 10:50:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 190334.9 (52h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5472474
telemt_connections_bad_total 56091
telemt_handshake_timeouts_total 120613
telemt_upstream_connect_attempt_total 40006
telemt_upstream_connect_success_total 39750
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 40006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7629
telemt_me_reconnect_attempts_total 43033
telemt_me_reconnect_success_total 27942
telemt_me_reader_eof_total 30056
telemt_me_idle_close_by_peer_total 30055
telemt_me_route_drop_no_conn_total 2069129
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5017263
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19147
telemt_desync_full_logged_total 5251
telemt_desync_suppressed_total 13896
telemt_desync_frames_bucket_total{bucket="1_2"} 4685
telemt_desync_frames_bucket_total{bucket="3_10"} 7294
telemt_desync_frames_bucket_total{bucket="gt_10"} 7168
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28822
telemt_me_refill_failed_total 466
telemt_me_writer_restored_same_endpoint_total 27929
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 880
telemt_user_connections_total{user="hello"} 5018733
telemt_user_connections_current{user="hello"} 1695
telemt_user_octets_from_client{user="hello"} 77066380540 (71.77 GB)
telemt_user_octets_to_client{user="hello"} 1597554730665 (1.45 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89998.8 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020438
telemt_connections_bad_total 58349
telemt_handshake_timeouts_total 22440
telemt_upstream_connect_attempt_total 23689
telemt_upstream_connect_success_total 23395
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 23689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 2288
telemt_me_reconnect_attempts_total 26780
telemt_me_reconnect_success_total 16902
telemt_me_reader_eof_total 18096
telemt_me_idle_close_by_peer_total 18095
telemt_me_route_drop_no_conn_total 343238
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 834558
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2357
telemt_desync_full_logged_total 734
telemt_desync_suppressed_total 1623
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 994
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17451
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16894
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 836457
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 9080031401 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 292084789452 (272.03 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 219955.5 (61h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3886593
telemt_connections_bad_total 45774
telemt_handshake_timeouts_total 257593
telemt_upstream_connect_attempt_total 49673
telemt_upstream_connect_success_total 49652
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11045
telemt_me_reconnect_attempts_total 44369
telemt_me_reconnect_success_total 38374
telemt_me_reader_eof_total 40761
telemt_me_idle_close_by_peer_total 40759
telemt_me_route_drop_no_conn_total 1334786
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3249986
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10422
telemt_desync_full_logged_total 3539
telemt_desync_suppressed_total 6883
telemt_desync_frames_bucket_total{bucket="1_2"} 1883
telemt_desync_frames_bucket_total{bucket="3_10"} 3774
telemt_desync_frames_bucket_total{bucket="gt_10"} 4765
telemt_pool_swap_total 204
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38943
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38333
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 3249125
telemt_user_connections_current{user="hello"} 889
telemt_user_octets_from_client{user="hello"} 54900528168 (51.13 GB)
telemt_user_octets_to_client{user="hello"} 1164314826317 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 219958.1 (61h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2558115
telemt_connections_bad_total 23431
telemt_handshake_timeouts_total 324563
telemt_upstream_connect_attempt_total 68124
telemt_upstream_connect_success_total 65619
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 67850
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20763
telemt_me_reconnect_attempts_total 59294
telemt_me_reconnect_success_total 47634
telemt_me_reader_eof_total 51022
telemt_me_idle_close_by_peer_total 51014
telemt_me_route_drop_no_conn_total 852218
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2002830
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4057
telemt_desync_full_logged_total 1329
telemt_desync_suppressed_total 2728
telemt_desync_frames_bucket_total{bucket="1_2"} 1145
telemt_desync_frames_bucket_total{bucket="3_10"} 1658
telemt_desync_frames_bucket_total{bucket="gt_10"} 1254
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48412
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47610
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 778
telemt_user_connections_total{user="hello"} 2009086
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 29854534539 (27.80 GB)
telemt_user_octets_to_client{user="hello"} 721910307526 (672.33 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89391.5 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1006339
telemt_connections_bad_total 17466
telemt_handshake_timeouts_total 13205
telemt_upstream_connect_attempt_total 22284
telemt_upstream_connect_success_total 21681
telemt_upstream_connect_fail_total 603
telemt_upstream_connect_attempts_per_request{bucket="1"} 22284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 603
telemt_me_keepalive_timeout_total 1722
telemt_me_reconnect_attempts_total 76775
telemt_me_reconnect_success_total 17210
telemt_me_reader_eof_total 19481
telemt_me_idle_close_by_peer_total 19480
telemt_me_route_drop_no_conn_total 390871
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931210
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2528
telemt_desync_full_logged_total 788
telemt_desync_suppressed_total 1740
telemt_desync_frames_bucket_total{bucket="1_2"} 864
telemt_desync_frames_bucket_total{bucket="3_10"} 928
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19229
telemt_me_refill_failed_total 1856
telemt_me_writer_restored_same_endpoint_total 17205
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2019
telemt_user_connections_total{user="hello"} 931147
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 16599028652 (15.46 GB)
telemt_user_octets_to_client{user="hello"} 312084417944 (290.65 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 77
```