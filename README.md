# Server Metrics 2026-03-15 17:13:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 68367.1 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2371559
telemt_connections_bad_total 147913
telemt_handshake_timeouts_total 29822
telemt_upstream_connect_attempt_total 13348
telemt_upstream_connect_success_total 13291
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 14779
telemt_me_reconnect_success_total 9882
telemt_me_reader_eof_total 10564
telemt_me_idle_close_by_peer_total 10564
telemt_me_route_drop_no_conn_total 815840
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1980478
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7767
telemt_desync_full_logged_total 2107
telemt_desync_suppressed_total 5660
telemt_desync_frames_bucket_total{bucket="1_2"} 1890
telemt_desync_frames_bucket_total{bucket="3_10"} 2978
telemt_desync_frames_bucket_total{bucket="gt_10"} 2899
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10201
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9871
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 1979967
telemt_user_connections_current{user="hello"} 2401
telemt_user_octets_from_client{user="hello"} 29217471008 (27.21 GB)
telemt_user_octets_to_client{user="hello"} 751607827564 (699.99 GB)
telemt_user_unique_ips_current{user="hello"} 702
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 68368.1 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 915632
telemt_connections_bad_total 48926
telemt_handshake_timeouts_total 61751
telemt_upstream_connect_attempt_total 17158
telemt_upstream_connect_success_total 17073
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 17158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14508
telemt_me_reconnect_success_total 13311
telemt_me_reader_eof_total 14086
telemt_me_idle_close_by_peer_total 14086
telemt_me_route_drop_no_conn_total 236715
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706808
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2170
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1441
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 811
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13523
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13299
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 707048
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 10193491911 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 267783798328 (249.39 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 68367.8 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2058564
telemt_connections_bad_total 49481
telemt_handshake_timeouts_total 207004
telemt_upstream_connect_attempt_total 14837
telemt_upstream_connect_success_total 14768
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12596
telemt_me_reconnect_success_total 11327
telemt_me_reader_eof_total 12000
telemt_me_idle_close_by_peer_total 12000
telemt_me_route_drop_no_conn_total 533292
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1261703
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3240
telemt_desync_full_logged_total 1165
telemt_desync_suppressed_total 2075
telemt_desync_frames_bucket_total{bucket="1_2"} 745
telemt_desync_frames_bucket_total{bucket="3_10"} 1252
telemt_desync_frames_bucket_total{bucket="gt_10"} 1243
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11527
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11308
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 1257637
telemt_user_connections_current{user="hello"} 1384
telemt_user_octets_from_client{user="hello"} 19444579052 (18.11 GB)
telemt_user_octets_to_client{user="hello"} 448924982464 (418.09 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 68367.9 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982650
telemt_connections_bad_total 81421
telemt_handshake_timeouts_total 47874
telemt_upstream_connect_attempt_total 169376
telemt_upstream_connect_success_total 168828
telemt_upstream_connect_fail_total 548
telemt_upstream_connect_attempts_per_request{bucket="1"} 169376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 548
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 58773
telemt_me_reconnect_success_total 13350
telemt_me_reader_eof_total 15126
telemt_me_idle_close_by_peer_total 15126
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 228624
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606672
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1719
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 1262
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 606
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14908
telemt_me_refill_failed_total 1421
telemt_me_writer_restored_same_endpoint_total 13314
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1558
telemt_user_connections_total{user="hello"} 758294
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 14238774910 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 272600994293 (253.88 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 68368.7 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 994199
telemt_connections_bad_total 12073
telemt_handshake_timeouts_total 22266
telemt_upstream_connect_attempt_total 15123
telemt_upstream_connect_success_total 15041
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15316
telemt_me_reconnect_success_total 11623
telemt_me_reader_eof_total 12396
telemt_me_idle_close_by_peer_total 12396
telemt_me_route_drop_no_conn_total 248389
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822289
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2776
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 1841
telemt_desync_frames_bucket_total{bucket="1_2"} 860
telemt_desync_frames_bucket_total{bucket="3_10"} 1034
telemt_desync_frames_bucket_total{bucket="gt_10"} 882
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11878
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11615
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 822320
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 10226424824 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 291204044780 (271.20 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 112
```