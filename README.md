# Server Metrics 2026-03-14 10:30:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 189108.1 (52h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5427342
telemt_connections_bad_total 56088
telemt_handshake_timeouts_total 120176
telemt_upstream_connect_attempt_total 39767
telemt_upstream_connect_success_total 39511
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7602
telemt_me_reconnect_attempts_total 40221
telemt_me_reconnect_success_total 27755
telemt_me_reader_eof_total 29784
telemt_me_idle_close_by_peer_total 29783
telemt_me_route_drop_no_conn_total 2051170
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4973398
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18980
telemt_desync_full_logged_total 5196
telemt_desync_suppressed_total 13784
telemt_desync_frames_bucket_total{bucket="1_2"} 4655
telemt_desync_frames_bucket_total{bucket="3_10"} 7230
telemt_desync_frames_bucket_total{bucket="gt_10"} 7095
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28549
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 27742
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 794
telemt_user_connections_total{user="hello"} 4974850
telemt_user_connections_current{user="hello"} 1795
telemt_user_octets_from_client{user="hello"} 76178547044 (70.95 GB)
telemt_user_octets_to_client{user="hello"} 1583495779157 (1.44 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88772.2 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002557
telemt_connections_bad_total 57633
telemt_handshake_timeouts_total 21865
telemt_upstream_connect_attempt_total 23301
telemt_upstream_connect_success_total 23009
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 23301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_keepalive_timeout_total 2260
telemt_me_reconnect_attempts_total 26437
telemt_me_reconnect_success_total 16561
telemt_me_reader_eof_total 17751
telemt_me_idle_close_by_peer_total 17750
telemt_me_route_drop_no_conn_total 336593
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 818778
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2292
telemt_desync_full_logged_total 718
telemt_desync_suppressed_total 1574
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 972
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17105
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16553
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 820674
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 8899139609 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 287534367488 (267.79 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 218728.9 (60h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3857704
telemt_connections_bad_total 45744
telemt_handshake_timeouts_total 255094
telemt_upstream_connect_attempt_total 49386
telemt_upstream_connect_success_total 49365
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11023
telemt_me_reconnect_attempts_total 43174
telemt_me_reconnect_success_total 38174
telemt_me_reader_eof_total 40515
telemt_me_idle_close_by_peer_total 40514
telemt_me_route_drop_no_conn_total 1324107
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3224597
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10333
telemt_desync_full_logged_total 3517
telemt_desync_suppressed_total 6816
telemt_desync_frames_bucket_total{bucket="1_2"} 1871
telemt_desync_frames_bucket_total{bucket="3_10"} 3742
telemt_desync_frames_bucket_total{bucket="gt_10"} 4720
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38706
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 38133
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 532
telemt_user_connections_total{user="hello"} 3223736
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 54624293988 (50.87 GB)
telemt_user_octets_to_client{user="hello"} 1156024803457 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 218731.3 (60h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2543345
telemt_connections_bad_total 23420
telemt_handshake_timeouts_total 322379
telemt_upstream_connect_attempt_total 67678
telemt_upstream_connect_success_total 65173
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 67404
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20747
telemt_me_reconnect_attempts_total 58938
telemt_me_reconnect_success_total 47282
telemt_me_reader_eof_total 50666
telemt_me_idle_close_by_peer_total 50658
telemt_me_route_drop_no_conn_total 847781
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1991089
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4048
telemt_desync_full_logged_total 1324
telemt_desync_suppressed_total 2724
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1654
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48056
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47258
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 774
telemt_user_connections_total{user="hello"} 1997302
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 29765765775 (27.72 GB)
telemt_user_octets_to_client{user="hello"} 719652444486 (670.23 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88165.1 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 989286
telemt_connections_bad_total 16522
telemt_handshake_timeouts_total 12988
telemt_upstream_connect_attempt_total 22091
telemt_upstream_connect_success_total 21499
telemt_upstream_connect_fail_total 592
telemt_upstream_connect_attempts_per_request{bucket="1"} 22091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 592
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 73931
telemt_me_reconnect_success_total 17118
telemt_me_reader_eof_total 19304
telemt_me_idle_close_by_peer_total 19303
telemt_me_route_drop_no_conn_total 383443
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 915814
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2470
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 1700
telemt_desync_frames_bucket_total{bucket="1_2"} 841
telemt_desync_frames_bucket_total{bucket="3_10"} 913
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19051
telemt_me_refill_failed_total 1770
telemt_me_writer_restored_same_endpoint_total 17113
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1933
telemt_user_connections_total{user="hello"} 915755
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 16336083532 (15.21 GB)
telemt_user_octets_to_client{user="hello"} 307226131280 (286.13 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 87
```