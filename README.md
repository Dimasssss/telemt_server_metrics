# Server Metrics 2026-03-13 15:00:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 118889.8 (33h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3676683
telemt_connections_bad_total 37418
telemt_handshake_timeouts_total 73837
telemt_upstream_connect_attempt_total 23181
telemt_upstream_connect_success_total 23049
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 23181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 2182
telemt_me_reconnect_attempts_total 27213
telemt_me_reconnect_success_total 17126
telemt_me_reader_eof_total 18406
telemt_me_idle_close_by_peer_total 18405
telemt_me_route_drop_no_conn_total 1362920
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3367887
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13812
telemt_desync_full_logged_total 3635
telemt_desync_suppressed_total 10177
telemt_desync_frames_bucket_total{bucket="1_2"} 3484
telemt_desync_frames_bucket_total{bucket="3_10"} 5235
telemt_desync_frames_bucket_total{bucket="gt_10"} 5093
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 17678
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17113
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 3367614
telemt_user_connections_current{user="hello"} 1882
telemt_user_octets_from_client{user="hello"} 46153061544 (42.98 GB)
telemt_user_octets_to_client{user="hello"} 1063228185248 (990.21 GB)
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18553.6 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264434
telemt_connections_bad_total 14512
telemt_handshake_timeouts_total 6518
telemt_upstream_connect_attempt_total 4481
telemt_upstream_connect_success_total 4397
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 4481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 5716
telemt_me_reconnect_success_total 3426
telemt_me_reader_eof_total 3636
telemt_me_idle_close_by_peer_total 3636
telemt_me_route_drop_no_conn_total 95717
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236494
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 915
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 686
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 295
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3537
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3419
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 236522
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 2410505300 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 66584512152 (62.01 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 148510.2 (41h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2728859
telemt_connections_bad_total 27406
telemt_handshake_timeouts_total 181395
telemt_upstream_connect_attempt_total 33390
telemt_upstream_connect_success_total 33380
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3255
telemt_me_reconnect_attempts_total 28221
telemt_me_reconnect_success_total 25673
telemt_me_reader_eof_total 27220
telemt_me_idle_close_by_peer_total 27219
telemt_me_route_drop_no_conn_total 919817
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2236060
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8009
telemt_desync_full_logged_total 2632
telemt_desync_suppressed_total 5377
telemt_desync_frames_bucket_total{bucket="1_2"} 1266
telemt_desync_frames_bucket_total{bucket="3_10"} 2923
telemt_desync_frames_bucket_total{bucket="gt_10"} 3820
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 25971
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25632
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 2235427
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 36909444712 (34.37 GB)
telemt_user_octets_to_client{user="hello"} 788749991701 (734.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 148510.8 (41h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1739775
telemt_connections_bad_total 18126
telemt_handshake_timeouts_total 130844
telemt_upstream_connect_attempt_total 46832
telemt_upstream_connect_success_total 44504
telemt_upstream_connect_fail_total 2191
telemt_upstream_connect_attempts_per_request{bucket="1"} 46558
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11851
telemt_me_reconnect_attempts_total 40250
telemt_me_reconnect_success_total 31280
telemt_me_reader_eof_total 33623
telemt_me_idle_close_by_peer_total 33616
telemt_me_route_drop_no_conn_total 622062
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1452573
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2918
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 1976
telemt_desync_frames_bucket_total{bucket="1_2"} 776
telemt_desync_frames_bucket_total{bucket="3_10"} 1216
telemt_desync_frames_bucket_total{bucket="gt_10"} 926
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 31795
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31256
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 1457285
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 22747607933 (21.19 GB)
telemt_user_octets_to_client{user="hello"} 558088088906 (519.76 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17946.5 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285790
telemt_connections_bad_total 3945
telemt_handshake_timeouts_total 2687
telemt_upstream_connect_attempt_total 3849
telemt_upstream_connect_success_total 3730
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 3849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 12075
telemt_me_reconnect_success_total 2813
telemt_me_reader_eof_total 3136
telemt_me_idle_close_by_peer_total 3136
telemt_me_route_drop_no_conn_total 112409
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267166
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 824
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3113
telemt_me_refill_failed_total 288
telemt_me_writer_restored_same_endpoint_total 2809
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 267145
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 3063490356 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 86657164572 (80.71 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 137
```