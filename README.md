# Server Metrics 2026-03-14 10:56:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 190641.7 (52h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5483549
telemt_connections_bad_total 56093
telemt_handshake_timeouts_total 120870
telemt_upstream_connect_attempt_total 40042
telemt_upstream_connect_success_total 39786
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 40042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7629
telemt_me_reconnect_attempts_total 43069
telemt_me_reconnect_success_total 27978
telemt_me_reader_eof_total 30092
telemt_me_idle_close_by_peer_total 30091
telemt_me_route_drop_no_conn_total 2073685
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5027528
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19188
telemt_desync_full_logged_total 5260
telemt_desync_suppressed_total 13928
telemt_desync_frames_bucket_total{bucket="1_2"} 4688
telemt_desync_frames_bucket_total{bucket="3_10"} 7315
telemt_desync_frames_bucket_total{bucket="gt_10"} 7185
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28858
telemt_me_refill_failed_total 466
telemt_me_writer_restored_same_endpoint_total 27965
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 880
telemt_user_connections_total{user="hello"} 5028988
telemt_user_connections_current{user="hello"} 1619
telemt_user_octets_from_client{user="hello"} 77340942292 (72.03 GB)
telemt_user_octets_to_client{user="hello"} 1601042736541 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90305.8 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1024705
telemt_connections_bad_total 58365
telemt_handshake_timeouts_total 22670
telemt_upstream_connect_attempt_total 23809
telemt_upstream_connect_success_total 23515
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 23809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 258
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 2288
telemt_me_reconnect_attempts_total 27976
telemt_me_reconnect_success_total 16977
telemt_me_reader_eof_total 18210
telemt_me_idle_close_by_peer_total 18209
telemt_me_route_drop_no_conn_total 344961
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 838394
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2382
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1643
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 1007
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17565
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 16969
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 840291
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 9106121565 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 293528830016 (273.37 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 220262.3 (61h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3893880
telemt_connections_bad_total 45782
telemt_handshake_timeouts_total 258206
telemt_upstream_connect_attempt_total 49711
telemt_upstream_connect_success_total 49690
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11045
telemt_me_reconnect_attempts_total 44407
telemt_me_reconnect_success_total 38412
telemt_me_reader_eof_total 40800
telemt_me_idle_close_by_peer_total 40798
telemt_me_route_drop_no_conn_total 1337333
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3256393
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10456
telemt_desync_full_logged_total 3550
telemt_desync_suppressed_total 6906
telemt_desync_frames_bucket_total{bucket="1_2"} 1890
telemt_desync_frames_bucket_total{bucket="3_10"} 3786
telemt_desync_frames_bucket_total{bucket="gt_10"} 4780
telemt_pool_swap_total 204
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38982
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38371
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 3255538
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 54967348764 (51.19 GB)
telemt_user_octets_to_client{user="hello"} 1165795960865 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 220265.1 (61h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2561536
telemt_connections_bad_total 23434
telemt_handshake_timeouts_total 325063
telemt_upstream_connect_attempt_total 68226
telemt_upstream_connect_success_total 65721
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 67952
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20766
telemt_me_reconnect_attempts_total 59396
telemt_me_reconnect_success_total 47736
telemt_me_reader_eof_total 51125
telemt_me_idle_close_by_peer_total 51117
telemt_me_route_drop_no_conn_total 853066
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2005585
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
telemt_me_writer_removed_unexpected_total 48515
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47712
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 779
telemt_user_connections_total{user="hello"} 2011854
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 29880982303 (27.83 GB)
telemt_user_octets_to_client{user="hello"} 722504929598 (672.89 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89698.8 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1010433
telemt_connections_bad_total 17707
telemt_handshake_timeouts_total 13275
telemt_upstream_connect_attempt_total 22311
telemt_upstream_connect_success_total 21708
telemt_upstream_connect_fail_total 603
telemt_upstream_connect_attempts_per_request{bucket="1"} 22311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 603
telemt_me_keepalive_timeout_total 1722
telemt_me_reconnect_attempts_total 76802
telemt_me_reconnect_success_total 17237
telemt_me_reader_eof_total 19508
telemt_me_idle_close_by_peer_total 19507
telemt_me_route_drop_no_conn_total 392721
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 934875
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2532
telemt_desync_full_logged_total 790
telemt_desync_suppressed_total 1742
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 928
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19256
telemt_me_refill_failed_total 1856
telemt_me_writer_restored_same_endpoint_total 17232
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2019
telemt_user_connections_total{user="hello"} 934812
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 16641187356 (15.50 GB)
telemt_user_octets_to_client{user="hello"} 313891911516 (292.33 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 87
```