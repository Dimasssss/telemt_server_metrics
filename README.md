# Server Metrics 2026-03-14 02:24:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 159943.5 (44h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4666907
telemt_connections_bad_total 39816
telemt_handshake_timeouts_total 108406
telemt_upstream_connect_attempt_total 33801
telemt_upstream_connect_success_total 33575
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 33801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 6713
telemt_me_reconnect_attempts_total 33416
telemt_me_reconnect_success_total 23276
telemt_me_reader_eof_total 24962
telemt_me_idle_close_by_peer_total 24961
telemt_me_route_drop_no_conn_total 1766400
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4278977
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16755
telemt_desync_full_logged_total 4518
telemt_desync_suppressed_total 12237
telemt_desync_frames_bucket_total{bucket="1_2"} 4186
telemt_desync_frames_bucket_total{bucket="3_10"} 6393
telemt_desync_frames_bucket_total{bucket="gt_10"} 6176
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 23926
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23263
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 650
telemt_user_connections_total{user="hello"} 4280831
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 62884972600 (58.57 GB)
telemt_user_octets_to_client{user="hello"} 1353268328061 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59607.2 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695677
telemt_connections_bad_total 50961
telemt_handshake_timeouts_total 13104
telemt_upstream_connect_attempt_total 16719
telemt_upstream_connect_success_total 16467
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 16719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 2059
telemt_me_reconnect_attempts_total 14888
telemt_me_reconnect_success_total 11444
telemt_me_reader_eof_total 12150
telemt_me_idle_close_by_peer_total 12149
telemt_me_route_drop_no_conn_total 233912
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 556634
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1670
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 1213
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 724
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11709
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11436
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 558585
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 5966797817 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 179180133520 (166.87 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 189563.7 (52h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3374147
telemt_connections_bad_total 34965
telemt_handshake_timeouts_total 223275
telemt_upstream_connect_attempt_total 42658
telemt_upstream_connect_success_total 42637
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10419
telemt_me_reconnect_attempts_total 37853
telemt_me_reconnect_success_total 32892
telemt_me_reader_eof_total 34930
telemt_me_idle_close_by_peer_total 34929
telemt_me_route_drop_no_conn_total 1156742
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2807629
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9328
telemt_desync_full_logged_total 3116
telemt_desync_suppressed_total 6212
telemt_desync_frames_bucket_total{bucket="1_2"} 1607
telemt_desync_frames_bucket_total{bucket="3_10"} 3374
telemt_desync_frames_bucket_total{bucket="gt_10"} 4347
telemt_pool_swap_total 178
telemt_me_writer_removed_unexpected_total 33355
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32851
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 2806854
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 45155329692 (42.05 GB)
telemt_user_octets_to_client{user="hello"} 1004487734217 (935.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 189566.4 (52h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2252610
telemt_connections_bad_total 22965
telemt_handshake_timeouts_total 245855
telemt_upstream_connect_attempt_total 59394
telemt_upstream_connect_success_total 56932
telemt_upstream_connect_fail_total 2325
telemt_upstream_connect_attempts_per_request{bucket="1"} 59120
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2324
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20416
telemt_me_reconnect_attempts_total 49509
telemt_me_reconnect_success_total 40478
telemt_me_reader_eof_total 43405
telemt_me_idle_close_by_peer_total 43398
telemt_me_route_drop_no_conn_total 771019
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1798459
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 41108
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40454
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 1804386
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 27584738135 (25.69 GB)
telemt_user_octets_to_client{user="hello"} 666196102154 (620.44 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58999.7 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695649
telemt_connections_bad_total 7908
telemt_handshake_timeouts_total 8658
telemt_upstream_connect_attempt_total 14904
telemt_upstream_connect_success_total 14492
telemt_upstream_connect_fail_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 14904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 412
telemt_me_keepalive_timeout_total 1502
telemt_me_reconnect_attempts_total 43699
telemt_me_reconnect_success_total 11535
telemt_me_reader_eof_total 12846
telemt_me_idle_close_by_peer_total 12845
telemt_me_route_drop_no_conn_total 264012
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 647779
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1679
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 12644
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11530
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1109
telemt_user_connections_total{user="hello"} 647665
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 11884420528 (11.07 GB)
telemt_user_octets_to_client{user="hello"} 210761596960 (196.29 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 33
```