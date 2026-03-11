# Server Metrics 2026-03-11 13:29:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 82962.0 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1957372
telemt_connections_bad_total 27775
telemt_handshake_timeouts_total 50310
telemt_upstream_connect_attempt_total 17266
telemt_upstream_connect_success_total 17256
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 907
telemt_me_reconnect_attempts_total 25879
telemt_me_reconnect_success_total 13046
telemt_me_reader_eof_total 14097
telemt_me_idle_close_by_peer_total 14097
telemt_me_route_drop_no_conn_total 720120
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1788487
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9430
telemt_desync_full_logged_total 2552
telemt_desync_suppressed_total 6878
telemt_desync_frames_bucket_total{bucket="1_2"} 2332
telemt_desync_frames_bucket_total{bucket="3_10"} 3642
telemt_desync_frames_bucket_total{bucket="gt_10"} 3456
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13586
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13040
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 1787002
telemt_user_connections_current{user="hello"} 1455
telemt_user_octets_from_client{user="hello"} 23903696396 (22.26 GB)
telemt_user_octets_to_client{user="hello"} 510157172132 (475.12 GB)
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83018.4 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 742334
telemt_connections_bad_total 13032
telemt_handshake_timeouts_total 51073
telemt_upstream_connect_attempt_total 26678
telemt_upstream_connect_success_total 23731
telemt_upstream_connect_fail_total 2947
telemt_upstream_connect_attempts_per_request{bucket="1"} 26678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10542
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2947
telemt_me_keepalive_timeout_total 2444
telemt_me_reconnect_attempts_total 17470
telemt_me_reconnect_success_total 16605
telemt_me_reader_eof_total 17572
telemt_me_idle_close_by_peer_total 17569
telemt_me_route_drop_no_conn_total 290238
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625731
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2729
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 1865
telemt_desync_frames_bucket_total{bucket="1_2"} 855
telemt_desync_frames_bucket_total{bucket="3_10"} 996
telemt_desync_frames_bucket_total{bucket="gt_10"} 878
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 16815
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16582
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 628218
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 6740224986 (6.28 GB)
telemt_user_octets_to_client{user="hello"} 179215712836 (166.91 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 83018.3 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1278431
telemt_connections_bad_total 8303
telemt_handshake_timeouts_total 117425
telemt_upstream_connect_attempt_total 22117
telemt_upstream_connect_success_total 21849
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 22117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 891
telemt_me_reconnect_attempts_total 32683
telemt_me_reconnect_success_total 16579
telemt_me_reader_eof_total 17844
telemt_me_idle_close_by_peer_total 17844
telemt_me_route_drop_no_conn_total 442705
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1104499
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2953
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 2075
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1112
telemt_desync_frames_bucket_total{bucket="gt_10"} 1127
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17302
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16568
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 723
telemt_user_connections_total{user="hello"} 1104876
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 13094232929 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 331067824421 (308.33 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 83018.7 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 921857
telemt_connections_bad_total 77212
telemt_handshake_timeouts_total 87501
telemt_upstream_connect_attempt_total 22624
telemt_upstream_connect_success_total 22624
telemt_upstream_connect_attempts_per_request{bucket="1"} 22624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 936
telemt_me_reconnect_attempts_total 19529
telemt_me_reconnect_success_total 18460
telemt_me_reader_eof_total 19582
telemt_me_idle_close_by_peer_total 19581
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 296573
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731827
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1561
telemt_desync_full_logged_total 615
telemt_desync_suppressed_total 946
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18687
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18432
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 731192
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 8463089752 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 212304644264 (197.72 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83018.4 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1004804
telemt_connections_bad_total 6816
telemt_handshake_timeouts_total 9273
telemt_upstream_connect_attempt_total 22697
telemt_upstream_connect_success_total 22599
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 22697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 966
telemt_me_reconnect_attempts_total 22380
telemt_me_reconnect_success_total 18307
telemt_me_reader_eof_total 19318
telemt_me_idle_close_by_peer_total 19318
telemt_me_route_drop_no_conn_total 354840
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 912235
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3670
telemt_desync_full_logged_total 1352
telemt_desync_suppressed_total 2318
telemt_desync_frames_bucket_total{bucket="1_2"} 1292
telemt_desync_frames_bucket_total{bucket="3_10"} 1386
telemt_desync_frames_bucket_total{bucket="gt_10"} 992
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18668
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18307
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 361
telemt_user_connections_total{user="hello"} 911978
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 13340657219 (12.42 GB)
telemt_user_octets_to_client{user="hello"} 326244835278 (303.84 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 104
```