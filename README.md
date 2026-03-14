# Server Metrics 2026-03-14 10:10:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 187881.2 (52h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5380220
telemt_connections_bad_total 54385
telemt_handshake_timeouts_total 119793
telemt_upstream_connect_attempt_total 39466
telemt_upstream_connect_success_total 39210
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7575
telemt_me_reconnect_attempts_total 38760
telemt_me_reconnect_success_total 27543
telemt_me_reader_eof_total 29531
telemt_me_idle_close_by_peer_total 29530
telemt_me_route_drop_no_conn_total 2034286
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4929092
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18810
telemt_desync_full_logged_total 5146
telemt_desync_suppressed_total 13664
telemt_desync_frames_bucket_total{bucket="1_2"} 4614
telemt_desync_frames_bucket_total{bucket="3_10"} 7184
telemt_desync_frames_bucket_total{bucket="gt_10"} 7012
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28296
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27530
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 753
telemt_user_connections_total{user="hello"} 4930537
telemt_user_connections_current{user="hello"} 1556
telemt_user_octets_from_client{user="hello"} 75651410552 (70.46 GB)
telemt_user_octets_to_client{user="hello"} 1571574573533 (1.43 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87545.1 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985393
telemt_connections_bad_total 56651
telemt_handshake_timeouts_total 21104
telemt_upstream_connect_attempt_total 23028
telemt_upstream_connect_success_total 22737
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 23028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 2252
telemt_me_reconnect_attempts_total 26210
telemt_me_reconnect_success_total 16336
telemt_me_reader_eof_total 17524
telemt_me_idle_close_by_peer_total 17523
telemt_me_route_drop_no_conn_total 330425
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804106
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2268
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1559
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 16878
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16328
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 805996
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 8758255157 (8.16 GB)
telemt_user_octets_to_client{user="hello"} 280613983432 (261.34 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 217501.8 (60h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3827909
telemt_connections_bad_total 45641
telemt_handshake_timeouts_total 253065
telemt_upstream_connect_attempt_total 49074
telemt_upstream_connect_success_total 49053
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10991
telemt_me_reconnect_attempts_total 42914
telemt_me_reconnect_success_total 37915
telemt_me_reader_eof_total 40250
telemt_me_idle_close_by_peer_total 40249
telemt_me_route_drop_no_conn_total 1314670
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3197708
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10288
telemt_desync_full_logged_total 3497
telemt_desync_suppressed_total 6791
telemt_desync_frames_bucket_total{bucket="1_2"} 1860
telemt_desync_frames_bucket_total{bucket="3_10"} 3723
telemt_desync_frames_bucket_total{bucket="gt_10"} 4705
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38441
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37874
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 3196870
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 53926243168 (50.22 GB)
telemt_user_octets_to_client{user="hello"} 1146637749861 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 217504.4 (60h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2526207
telemt_connections_bad_total 23404
telemt_handshake_timeouts_total 319195
telemt_upstream_connect_attempt_total 67376
telemt_upstream_connect_success_total 64873
telemt_upstream_connect_fail_total 2366
telemt_upstream_connect_attempts_per_request{bucket="1"} 67102
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2365
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20725
telemt_me_reconnect_attempts_total 58683
telemt_me_reconnect_success_total 47031
telemt_me_reader_eof_total 50390
telemt_me_idle_close_by_peer_total 50382
telemt_me_route_drop_no_conn_total 843005
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1978322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4044
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 2722
telemt_desync_frames_bucket_total{bucket="1_2"} 1139
telemt_desync_frames_bucket_total{bucket="3_10"} 1653
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 47802
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47007
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 771
telemt_user_connections_total{user="hello"} 1984519
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 29589454711 (27.56 GB)
telemt_user_octets_to_client{user="hello"} 715946352602 (666.78 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86937.8 (24h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 971182
telemt_connections_bad_total 15566
telemt_handshake_timeouts_total 12799
telemt_upstream_connect_attempt_total 21930
telemt_upstream_connect_success_total 21343
telemt_upstream_connect_fail_total 587
telemt_upstream_connect_attempts_per_request{bucket="1"} 21930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 587
telemt_me_keepalive_timeout_total 1695
telemt_me_reconnect_attempts_total 72444
telemt_me_reconnect_success_total 17007
telemt_me_reader_eof_total 19150
telemt_me_idle_close_by_peer_total 19149
telemt_me_route_drop_no_conn_total 371694
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 899668
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2387
telemt_desync_full_logged_total 745
telemt_desync_suppressed_total 1642
telemt_desync_frames_bucket_total{bucket="1_2"} 810
telemt_desync_frames_bucket_total{bucket="3_10"} 881
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18897
telemt_me_refill_failed_total 1727
telemt_me_writer_restored_same_endpoint_total 17002
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1890
telemt_user_connections_total{user="hello"} 899611
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 15879736268 (14.79 GB)
telemt_user_octets_to_client{user="hello"} 302045790284 (281.30 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 92
```