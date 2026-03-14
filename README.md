# Server Metrics 2026-03-14 09:24:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 185120.4 (51h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5274102
telemt_connections_bad_total 50161
telemt_handshake_timeouts_total 118516
telemt_upstream_connect_attempt_total 38847
telemt_upstream_connect_success_total 38596
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 38847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 7504
telemt_me_reconnect_attempts_total 38279
telemt_me_reconnect_success_total 27065
telemt_me_reader_eof_total 29043
telemt_me_idle_close_by_peer_total 29042
telemt_me_route_drop_no_conn_total 1994068
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4831376
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18470
telemt_desync_full_logged_total 5048
telemt_desync_suppressed_total 13422
telemt_desync_frames_bucket_total{bucket="1_2"} 4558
telemt_desync_frames_bucket_total{bucket="3_10"} 7032
telemt_desync_frames_bucket_total{bucket="gt_10"} 6880
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 27811
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27052
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 746
telemt_user_connections_total{user="hello"} 4832857
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 74092328784 (69.00 GB)
telemt_user_octets_to_client{user="hello"} 1544149942665 (1.40 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84784.2 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 943556
telemt_connections_bad_total 54409
telemt_handshake_timeouts_total 19128
telemt_upstream_connect_attempt_total 22509
telemt_upstream_connect_success_total 22221
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 22509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9843
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 2215
telemt_me_reconnect_attempts_total 25442
telemt_me_reconnect_success_total 15955
telemt_me_reader_eof_total 17101
telemt_me_idle_close_by_peer_total 17100
telemt_me_route_drop_no_conn_total 315244
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767584
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2179
telemt_desync_full_logged_total 685
telemt_desync_suppressed_total 1494
telemt_desync_frames_bucket_total{bucket="1_2"} 495
telemt_desync_frames_bucket_total{bucket="3_10"} 935
telemt_desync_frames_bucket_total{bucket="gt_10"} 749
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16480
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 15947
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 769481
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 8181405925 (7.62 GB)
telemt_user_octets_to_client{user="hello"} 266234138320 (247.95 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 214741.0 (59h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3757432
telemt_connections_bad_total 44523
telemt_handshake_timeouts_total 248326
telemt_upstream_connect_attempt_total 48486
telemt_upstream_connect_success_total 48465
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10880
telemt_me_reconnect_attempts_total 42459
telemt_me_reconnect_success_total 37466
telemt_me_reader_eof_total 39781
telemt_me_idle_close_by_peer_total 39780
telemt_me_route_drop_no_conn_total 1290501
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3137868
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10132
telemt_desync_full_logged_total 3445
telemt_desync_suppressed_total 6687
telemt_desync_frames_bucket_total{bucket="1_2"} 1801
telemt_desync_frames_bucket_total{bucket="3_10"} 3673
telemt_desync_frames_bucket_total{bucket="gt_10"} 4658
telemt_pool_swap_total 201
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 37988
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37425
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 3137039
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 53203173612 (49.55 GB)
telemt_user_octets_to_client{user="hello"} 1122079574105 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 214743.4 (59h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2485035
telemt_connections_bad_total 23370
telemt_handshake_timeouts_total 307331
telemt_upstream_connect_attempt_total 66576
telemt_upstream_connect_success_total 64078
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 66302
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20622
telemt_me_reconnect_attempts_total 58020
telemt_me_reconnect_success_total 46372
telemt_me_reader_eof_total 49717
telemt_me_idle_close_by_peer_total 49710
telemt_me_route_drop_no_conn_total 832152
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1951321
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4020
telemt_desync_full_logged_total 1313
telemt_desync_suppressed_total 2707
telemt_desync_frames_bucket_total{bucket="1_2"} 1129
telemt_desync_frames_bucket_total{bucket="3_10"} 1644
telemt_desync_frames_bucket_total{bucket="gt_10"} 1247
telemt_pool_swap_total 187
telemt_me_writer_removed_unexpected_total 47133
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46348
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1957482
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 29327794203 (27.31 GB)
telemt_user_octets_to_client{user="hello"} 708559435494 (659.90 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84176.6 (23h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 927861
telemt_connections_bad_total 13225
telemt_handshake_timeouts_total 12034
telemt_upstream_connect_attempt_total 21348
telemt_upstream_connect_success_total 20778
telemt_upstream_connect_fail_total 570
telemt_upstream_connect_attempts_per_request{bucket="1"} 21348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 570
telemt_me_keepalive_timeout_total 1678
telemt_me_reconnect_attempts_total 67982
telemt_me_reconnect_success_total 16580
telemt_me_reader_eof_total 18595
telemt_me_idle_close_by_peer_total 18594
telemt_me_route_drop_no_conn_total 355565
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 861726
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2281
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1569
telemt_desync_frames_bucket_total{bucket="1_2"} 750
telemt_desync_frames_bucket_total{bucket="3_10"} 861
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18341
telemt_me_refill_failed_total 1601
telemt_me_writer_restored_same_endpoint_total 16575
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1761
telemt_user_connections_total{user="hello"} 861665
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 15418250788 (14.36 GB)
telemt_user_octets_to_client{user="hello"} 291544379944 (271.52 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 94
```